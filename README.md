# API_REST_web3_CP303061X
Projeto baseado em arquitetura de microsserviços, composto por três domínios independentes:

👤 Clientes

📦 Produtos

🧾 Pedidos

Cada serviço possui:

- Banco de dados próprio

- API REST própria

- Execução independente

- Comunicação síncrona via HTTP (REST)

# Instruções do Projeto

1. Clonar o repositório:

`git clone https://github.com/Rafaela-Mello/API_REST_web3_CP303061X.git`

`cd nodejs-microservices`

2. Instalar as dependências (em cada serviço):

`npm install`

3. Executando cada serviço:

`npm start`

4. Cada microsserviço roda em sua própria porta (definida no .env.example).

5. Utilize o ThunderClient (extensão do VS Code) ou qualquer cliente HTTP (Postman, Insomnia) para testar os endpoints.