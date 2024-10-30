# API E-Commerce

Uma API Flask para gerenciar produtos e carrinhos de compras em um sistema de e-commerce.

## Tecnologias Utilizadas

- Flask
- Flask-RESTful
- SQLAlchemy 

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/EduardoCoura/API-FLASK.git
2. Navegue até o diretório do projeto:
   ```bash
   cd seu-repositorio
3. Crie um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
4. Instale as dependências:
   ```bash
   pip install -r requirements.txt

## Configuração
Configure suas variáveis de ambiente, se necessário.

## Executando a API
Para iniciar a API, execute o seguinte comando:
```bash
   python app.py
```
A API estará disponível em http://127.0.0.1:5000/.

## Endpoints
Produtos:

➣ `GET /produtos`: Retorna a lista de produtos.

➣ `POST /produtos`: Adiciona um novo produto.

➣ `GET /produtos/<id>`: Retorna detalhes de um produto específico.

➣ `PUT /produtos/<id>`: Atualiza informações de um produto.

➣ `DELETE /produtos/<id>`: Remove um produto.

Carrinho:

➣ `GET /carrinho`: Retorna os produtos no carrinho.

➣ `POST /carrinho`: Adiciona um produto ao carrinho.

➣ `DELETE /carrinho/<id>`: Remove um produto do carrinho.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
