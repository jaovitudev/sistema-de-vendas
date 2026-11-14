# 🛍️ Sistema de Vendas

> 📊 **Registre vendas. Acompanhe resultados. Visualize seus dados.**
>
> Aplicação web simples, feita com Python e Streamlit, para cadastrar vendas em um arquivo CSV e acompanhar o faturamento em um painel interativo.

## ✨ Recursos

- 📝 Cadastro de vendas com data, vendedor, produto, quantidade e valor.
- 💾 Armazenamento dos registros em `vendas.csv`.
- 📋 Tabela com as vendas cadastradas.
- 💰 Indicador de faturamento total.
- 📊 Gráfico de valores por vendedor e produto.
- 🥧 Gráfico de participação dos produtos nas vendas.

## 🧰 Tecnologias

- 🐍 Python
- 🎈 [Streamlit](https://streamlit.io/) — interface web
- 🐼 [Pandas](https://pandas.pydata.org/) — leitura e organização dos dados
- 📈 [Plotly Express](https://plotly.com/python/plotly-express/) — gráficos interativos
- 📄 CSV — armazenamento local dos registros

## 🚀 Como executar

### 1. Pré-requisitos

Instale o [Python](https://www.python.org/downloads/) e abra um terminal na pasta do projeto.

### 2. Instale as dependências

```bash
python -m pip install -r requirements.txt
```

### 3. Inicie a aplicação

```bash
python -m streamlit run main.py
```

O Streamlit exibirá um endereço local no terminal, normalmente [http://localhost:8501](http://localhost:8501). Abra esse endereço no navegador.

## 🧾 Como usar

1. Preencha os campos na barra lateral: data, vendedor, produto, quantidade e valor.
2. Clique em **Cadastrar venda**.
3. Consulte os registros na tabela e os indicadores e gráficos no painel.

## 📁 Estrutura do projeto

```text
sistema-de-vendas.py/
├── main.py           # Aplicação Streamlit
├── requirements.txt  # Dependências do projeto
├── vendas.csv        # Dados das vendas
└── README.md         # Documentação do projeto
```

## 💡 Observações

- O arquivo `vendas.csv` deve permanecer junto com `main.py`.
- Os registros ficam salvos localmente no CSV; faça uma cópia de segurança para preservar os dados.
- Para começar com uma planilha vazia, mantenha os cabeçalhos `data,vendedor,produto,quantidade,valor`.

## 👤 Autor

Desenvolvido por **jaovitudev**.

---

⭐ Se este projeto foi útil, deixe uma estrela no repositório!
