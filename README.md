# Gerador de Lista de Arquivos

Script Python que lê os arquivos de uma pasta e exporta seus nomes para uma planilha Excel.

## Requisitos

* Python 3
* openpyxl
* pathlib (nativo)
  
Instalação:

```bash
pip install openpyxl
```

## Execução

1. Configure a pasta desejada na variável `PASTA`.
2. Execute o script:

```bash
python script.py
```

## Resultado

Será gerado o arquivo:

```text
lista_arquivos.xlsx
```

contendo os nomes dos arquivos encontrados na pasta especificada.

## Bibliotecas utilizadas

* pathlib
* openpyxl

