# TheX - Sales API

O projeto em Python TheX - Sales API desempenha um papel crítico na administração de transações de vendas dentro do ecossistema Market-TheX. É responsável por lidar com o registro e administração de vendas entre clientes e produtos. Abaixo, você encontrará informações-chave sobre este projeto:

- **Gerenciamento de Projeto:** Pipenv
- **Linguagem:** Python
- **Versão do Python:** 3.9

## Visão Geral

O projeto Sales API é projetado para gerenciar operações de vendas, facilitando o registro de transações e garantindo a integração de produtos e clientes.

## Dependências

A API de Vendas utiliza várias bibliotecas Python para aprimorar sua funcionalidade:

- **Flask:** Um framework web leve e poderoso para Python, que permite a criação de aplicativos web e APIs. [Mais informações](https://flask.palletsprojects.com/)

- **SQLAlchemy:** Um popular toolkit SQL Python e biblioteca de Mapeamento Objeto-Relacional (ORM) que simplifica operações de banco de dados. [Mais informações](https://www.sqlalchemy.org/)

- **SQLite3:** Um mecanismo de banco de dados SQL leve, sem servidor e autocontido, adequado para incorporação em aplicativos Python. [Detalhes](https://docs.python.org/3/library/sqlite3.html)

## Como Começar

1. Clone este repositório em seu ambiente de desenvolvimento local.

2. Abra o projeto em seu ambiente de desenvolvimento Python favorito (por exemplo, Visual Studio Code, PyCharm).

    2.1 Crie seu ambiente virtual
    - `~/.pyenv/versions/3.9.15/bin/python -m venv .venv`

3. Configure um banco de dados e ajuste as configurações de conexão em `config.py` para corresponder à configuração do seu banco de dados.

4. Execute o projeto e você pode acessar a API de Vendas através da URL: `http://localhost:5000/api/sales`.

## Exemplos de Uso

Aqui estão alguns exemplos de uso para a API de Vendas:

- **Registro de Venda:** Para registrar uma nova venda, faça uma solicitação POST para `http://localhost:5000/api/sales` com os detalhes da venda no corpo da solicitação.

- **Recuperação de Informações de Vendas:** Para recuperar informações sobre uma venda específica, faça uma solicitação GET para `http://localhost:5000/api/sales/{saleID}`.

- **Listagem de Todas as Vendas:** Para obter uma lista de todas as transações de vendas, faça uma solicitação GET para `http://localhost:5000/api/sales`.
