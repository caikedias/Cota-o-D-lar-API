# Cotação-Dólarimport requests
import json

# API de Cotações
cotacoes = requests.get("https://economia.awesomeapi.com.br/last/USD-BRL,EUR-BRL,BTC-BRL")
cotacoes = cotacoes.json()
cotacao_dolar = cotacoes['USDBRL']["bid"]

# PRINT COTACOES
print(cotacoes)
print(cotacao_dolar)



