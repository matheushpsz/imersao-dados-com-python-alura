# Dashboard de Salários na Área de Dados ✅

Breve descrição: dashboard em Streamlit que exibe análise de salários na área de dados (gráficos, tabelas e filtros). O script principal é `app.py` e as dependências estão em `requirements.txt`.

---

## 🔗 Link do app (deploy)
- Demo pública: **https://imersao-dados-com-python-alura-hspszmatheus.streamlit.app/**

---

## 🧰 Requisitos
- **Python 3.8+**
- **pip**

## ⚙️ Instalação (rápido)
1. Criar e ativar um ambiente virtual (recomendado):

```sh
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate
```

2. Instalar dependências:

```sh
pip install -r requirements.txt
```

## ▶️ Executando localmente
```sh
streamlit run app.py
```
Abra no navegador: `http://localhost:8501` (ou siga o endereço mostrado no terminal).

---

## 📂 Como usar o CSV local
Por padrão o app pode carregar dados de uma URL. Para usar o arquivo local `dados-imersao-final.csv`, abra `app.py` e substitua a linha de leitura remota por:

```py
df = pd.read_csv("dados-imersao-final.csv")
```

> **Nota:** verifique se o dataframe resultante não está vazio após os filtros.

---

## 🛠️ Troubleshooting (dicas)
- Se algum gráfico não aparecer, cheque o conteúdo de `df` e as colunas usadas nos filtros.
- Em caso de erro de dependência, confira as versões em `requirements.txt` e recrie o ambiente virtual.

---

## 🧾 Estrutura de arquivos
- `app.py` — aplicação Streamlit
- `requirements.txt` — dependências do projeto
- `dados-imersao-final.csv` — arquivo de dados (opcional)

---

## 🤝 Contribuição
Abra uma issue ou envie um pull request com melhorias.

## 📜 Licença
Escolha uma licença (ex.: MIT) ou remova esta seção se não aplicável.
