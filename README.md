Backend - Gerenciador de Dispositivos (API)
Este é o backend do nosso projeto, feito em Laravel. Ele funciona como uma API REST para gerenciar dispositivos.

📝 Propósito
Este projeto faz parte de um case para a vaga de Desenvolvedor da Meta Telecom, focado na criação de um CRUD para a futura plataforma Meta Tex, que visa a conectividade IoT. O objetivo é demonstrar a habilidade de construir uma API completa para um aplicativo frontend.

⚙️ Tecnologias Usadas
Framework: Laravel

Linguagem: PHP 8+

Gerenciador de Dependências: Composer

Banco de Dados: Postgres

🚀 Como Rodar o Projeto
Clone o repositório e entre na pasta.

Instale as dependências do Composer:

composer install

Configure o banco de dados: Crie o arquivo .env a partir do .env.example e atualize as credenciais do seu Postgres.

Execute as migrations para criar as tabelas no banco de dados:

php artisan migrate

Inicie o servidor local:

php artisan serve

A API estará disponível em http://127.0.0.1:8000.

📌 Endpoints da API
A API usa rotas de recurso, então os principais endpoints são:

GET /api/dispositivos: Lista todos os dispositivos.

POST /api/dispositivos: Cria um novo dispositivo.

GET /api/dispositivos/{id}: Exibe um dispositivo específico.

PUT /api/dispositivos/{id}: Atualiza um dispositivo.

DELETE /api/dispositivos/{id}: Deleta um dispositivo.