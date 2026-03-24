# Project Manager API

API para gerenciamento de projetos desenvolvida com FastAPI.

## Funcionalidades
- CRUD de projetos
- Validação de dados
- Tratamento global de erros

## Tecnologias
- FastAPI
- SQLModel
- SQLite

## Como rodar

```bash
# Criar ambiente virtual
python -m venv .venv
# Ativar ambiente
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

# Instalar dependências
pip install -r requirements.txt

# Rodar a aplicação
uvicorn main:app --reload
```

## Documentação

Acesse a documentação automática da API (Swagger) em: http://localhost:8000/docs

## Metas do projeto

1. CRUD completo de projetos com FastAPI 
(Status: Concluído)

2. Documentação do código com docstrings
(Status: Concluído)

3. Documentação automática da API (Swagger)
(Status: Concluído)

4. Adicionar testes com Pytest e cliente FastAPI
(Status: Pendente)

5. Refatorar para seguir boas práticas de Clean Code 
(Status: Pendente)