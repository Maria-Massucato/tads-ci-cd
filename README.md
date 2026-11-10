
# Laboratório CI/CD TADS

Projeto desenvolvido para a atividade prática de integração e entrega contínua (CI/CD), utilizando Python, Flask, Pytest, GitHub Actions e Render.

## Tecnologias utilizadas

- Python
- Flask
- Pytest
- Gunicorn
- GitHub Actions
- Render

## Rotas da API

| Método | Rota | Descrição |
|---|---|---|
| GET | `/` | Retorna a mensagem inicial e a versão da API |
| GET | `/saude` | Verifica se a API está funcionando |
| GET | `/tarefas` | Lista as tarefas cadastradas |

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
cd tads-ci-cd
```

### 2. Criar o ambiente virtual

```bash
python -m venv .venv
```

### 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 4. Executar a aplicação

```bash
python app.py
```

A API estará disponível em:

http://localhost:5000

## Executar os testes

```bash
python -m pytest -q
```

## Objetivo

Praticar a criação de uma API em Flask, a execução de testes automatizados e a configuração de um fluxo de integração e entrega contínua.
