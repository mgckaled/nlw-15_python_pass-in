<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD014 -->

# NLW 15 Unite - Python

<div align="center">
  <img alt="Made by mgckaled" src="https://img.shields.io/badge/made%20by-mgckaled-darkblue">
  <img alt="GitHub Repo Size" src="https://img.shields.io/github/repo-size/mgckaled/nlw-15_python_pass-in">
  <img alt="pylint badge" src="https://img.shields.io/badge/linting-pylint-yellowgreen">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</div>

## Projeto

Esta aplicação foi desenvolvida durante o Evento NLW 15 Unite da Rocketseat.

## Tecnologias

### Linguagem de Programação

- [`python`](https://www.python.org/) (v3.11.5)

### Gerenciadores de Ambiente Virtual

- [`pyenv`](https://github.com/pyenv/pyenv)
- [`pipenv`](https://pipenv.pypa.io/en/latest/)

### Bibliotecas Instaladas (Packages)

- [`pylint`](https://pylint.pycqa.org/en/latest/index.html)
- [`pre-commit`](https://pre-commit.com/)
- [`pillow`](https://pypi.org/project/pillow/)
- [`flask`](https://flask.palletsprojects.com/en/3.0.x/)
- [`sqlalchemy`](https://www.sqlalchemy.org/)
- [`flask-cors`](https://pypi.org/project/Flask-Cors/)
- [`pytest`](https://docs.pytest.org/en/8.2.x/)

## Como clonar o projeto?

1. Certifique-se de que está usando o `pyenv` e o `pipenv` para gerenciar as dependências do projeto. Veja como instalar e configurar clicando nos respectivos links do tópico [Gerenciadores de Ambiente Virtual](#gerenciadores-de-ambiente-virtual).

2. Faça o clone pelo Github:

    ```shell
    $ git clone https://github.com/mgckaled/nlw-15_python_pass-in.git
    ```

3. Acesse o diretório:

    ```shell
    $ cd nlw-15_python_pass-in
    ```

4. Ative o ambiente virtual pelo terminal

    ```shell
    $ pipenv shell
    ```

5. Instale as dependências. (Certifique-se de estar utilzando a versão exata do python - 3.11.5)

    ```shell
    $ pipenv install
    ```

    ou, como um recurso de degurança,  dependências exatas do `requirements.txt`:

    ```shell
    $ pipenv install -r requirements.txt
    ```

6. Caso queira ativar o pylint dentro do Git com as configurações do `.pre-commit-config`:

    ```shell
    $ pre-commit install
    ```

## Licença

Distribuído sob a licença *MIT*. Veja [LICENSE](LICENSE) para mais informações.

---

<h5 align="center">
  2024 - <a href="https://github.com/mgckaled/">Marcel Kaled</a>
</h5>
