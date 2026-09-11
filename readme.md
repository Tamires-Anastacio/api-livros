# API de Livros

API de livros desenvolvida com **Python, FastAPI e MySQL**.

Sobre o projeto

Este projeto tem como objetivo desenvolver uma API para cadastro e gerenciamento de livros.

Cada livro possui:

* `id`: identificador numérico único;
* `titulo`: título do livro;
* `autor`: nome do autor;
* `ano_publicacao`: ano em que o livro foi publicado;
* `disponivel`: indica se o livro está disponível.

## Tecnologias utilizadas

* Python
* FastAPI
* MySQL
* SQLAlchemy
* PyMySQL
* Uvicorn

## Banco de dados

O banco de dados utilizado é:

`biblioteca`

A tabela principal é:

`livros`

## Execução do projeto

Primeiro, instale as dependências:

bash
pip install -r requirements.txt

Depois, execute a API:

bash
uvicorn app.main:app --reload


A API estará disponível em:

`http://127.0.0.1:8000`

## Documentação

A documentação automática do FastAPI pode ser acessada em:

`http://127.0.0.1:8000/docs`

## Rotas

| Método | Rota           | Função          |
| ------ | -------------- | --------------- |
| POST   | `/livros`      | Cadastrar livro |
| GET    | `/livros`      | Listar livros   |
| GET    | `/livros/{id}` | Consultar livro |
| PUT    | `/livros/{id}` | Atualizar livro |
| DELETE | `/livros/{id}` | Excluir livro   |

## Autor

Projeto desenvolvido como atividade acadêmica.
