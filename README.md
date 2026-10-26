# Flix API

A **Flix API** é uma API REST desenvolvida em Python, utilizando Django e Django REST Framework, com o objetivo de gerenciar informações sobre filmes, gêneros, atores e avaliações.

O projeto permite realizar operações de cadastro, consulta, atualização e exclusão de registros, além de contar com autenticação de usuários.

## Tecnologias utilizadas

- Python
- Django
- Django REST Framework
- Simple JWT
- SQLite

## Funcionalidades

- Gerenciamento de filmes.
- Cadastro de atores e gêneros.
- Avaliações de filmes.
- Autenticação com JWT.
- Operações CRUD por meio de endpoints REST.
- Consulta de estatísticas dos filmes.

## Requisitos

Para executar o projeto, é necessário ter instalado:

- Python
- Pip
- Dependências listadas no arquivo `requirements.txt`

## Instalação

Clone o repositório:

```bash
git clone https://github.com/rimarassi/flix_api.git
```

Acesse a pasta do projeto:

```bash
cd flix_api
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

## Executar o projeto

Aplique as migrações do banco de dados:

```bash
python manage.py migrate
```

Inicie o servidor:

```bash
python manage.py runserver
```

Após isso, a API estará disponível em:

http://127.0.0.1:8000/

## Integração com Flix App

Esta API também é utilizada como backend do projeto **Flix App**, desenvolvido com Streamlit.

Repositório do frontend: [github.com/rimarassi/flix_app](https://github.com/rimarassi/flix_app)
