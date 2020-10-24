# alura-imersao-dados
Imersão dados da Alura

# Dados
* [Dados do estado do Espirito Santo no ENEM em 2019](https://github.com/cleber-abreu/alura-imersao-dados/blob/main/MICRODADOS_ENEM_2019_ES-csv.zip)

  para obter diretamente no pandas:
  ```
  import pandas as pd

  dados = pd.read_csv(
    'https://github.com/cleber-abreu/alura-imersao-dados/blob/main/MICRODADOS_ENEM_2019_ES-csv.zip?raw=true', 
    compression="zip")
  ```
