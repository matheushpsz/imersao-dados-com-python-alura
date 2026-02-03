# imersao-dados-com-python-alura: Dashboard de Salários na Área de Dados

Este repositório contém um dashboard Streamlit para análise de salários na área de dados. O script principal é [app.py](app.py) e as dependências estão em [requirements.txt](requirements.txt). Há também o arquivo de dados local [dados-imersao-final.csv](dados-imersao-final.csv), embora o app atualmente carregue os dados de uma URL remota.

## Requisitos
- Python 3.8+  
- pip

## Instalação
1. Crie e ative um ambiente virtual (opcional, recomendado):
```sh
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate
```

2. Instale as dependências:
```sh
pip install -r requirements.txt
```

## Executando o projeto
Inicie o app Streamlit:
```sh
streamlit run app.py
```
Depois, abra no navegador: http://localhost:8501

## Observações
- O arquivo [app.py](app.py) atualmente carrega os dados a partir de um repositório remoto. Para usar o arquivo local [dados-imersao-final.csv](dados-imersao-final.csv), substitua a linha de leitura do CSV por:
```py
df = pd.read_csv("dados-imersao-final.csv")
```
- Se encontrar problemas com versões de pacotes, verifique [requirements.txt](requirements.txt) e ajuste seu ambiente conforme necessário.

## Estrutura de arquivos
- `app.py` — aplicação Streamlit com visualizações
- `requirements.txt` — dependências do projeto
- `dados-imersao-final.csv` — conjunto de dados (opcional, usado localmente se alterado)
