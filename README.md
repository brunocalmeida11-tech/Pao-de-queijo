# 🧀 Pão de Queijo API

## 📌 Sobre o projeto

O Pão de Queijo API é um projeto de uma cantina que permite visualizar produtos, adicionar itens ao carrinho e realizar pedidos.

O sistema foi desenvolvido utilizando Python no backend, SQLite para armazenar os dados e HTML, CSS e JavaScript no frontend.

## 🚀 Tecnologias utilizadas

- Python
- Flask
- SQLite
- HTML5
- CSS3
- JavaScript
- Pytest

## ⚙️ Como executar o projeto

### 1. Clonar o repositório

```bash
git clone URL_DO_SEU_REPOSITORIO
```

Entre na pasta do projeto:

```bash
cd pao-de-queijo-api
```

### 2. Criar o ambiente virtual

```bash
py -m venv venv
```

Ative o ambiente virtual no Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 4. Preparar o banco de dados

```bash
python seed.py
```

Esse comando prepara o banco de dados e adiciona alguns produtos iniciais.

### 5. Iniciar o servidor

```bash
python -m app
```

Depois, acesse no navegador:

http://127.0.0.1:5000

## 📡 Rotas da API

| Método | Rota | Função |
|---|---|---|
| GET | `/api/health` | Verifica se a API está funcionando |
| GET | `/api/products` | Lista os produtos |
| GET | `/api/products/<id>` | Consulta um produto |
| POST | `/api/products` | Cadastra um produto |
| PATCH | `/api/products/<id>/stock` | Atualiza o estoque |
| GET | `/api/orders` | Lista os pedidos |
| GET | `/api/orders/<id>` | Consulta um pedido |
| POST | `/api/orders` | Registra um pedido |

## 🧪 Testes

Para executar os testes automatizados, utilize:

```bash
pytest -q
```

## 📦 Funcionalidades

- Visualização do cardápio.
- Busca de produtos.
- Carrinho de compras.
- Cálculo do valor total.
- Registro de pedidos.
- Controle de estoque.
- Validação dos dados enviados para a API.
- Armazenamento dos pedidos no banco de dados.

## 👨‍💻 Observações

Este projeto foi desenvolvido para fins de estudo e demonstração. Ele não possui sistema de login nem pagamento online.

## 📄 Licença

Projeto desenvolvido para fins educacionais.
