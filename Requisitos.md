A aplicação foi feita em Python para ser ultilizada no Google Colab.

Comandos para rodar a aplicação: 

!pip install --upgrade gspread

from google.colab import auth
auth.authenticate_user()

import gspread
from google.auth import default
creds, _ = default()

gc = gspread.authorize(creds)
