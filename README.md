Frontend - Interface de Dispositivos
Este é o frontend do nosso projeto, feito em Angular. Ele é a interface para o usuário interagir com o backend.

📝 Propósito
O objetivo principal é criar uma interface amigável para a plataforma Meta Tex, demonstrando como o frontend pode consumir uma API REST completa para exibir, adicionar, editar e apagar dispositivos. Este projeto faz parte de um case para a vaga de Desenvolvedor da Meta Telecom.

⚙️ Tecnologias Usadas
Framework: Angular 6+

Linguagem: TypeScript

Gerenciador de Pacotes: npm

Estilo: Sass (SCSS), CSS, HTML

Controle de Versão: Git

🚀 Como Rodar o Projeto
Clone o repositório e entre na pasta.

Instale os pacotes do npm:

npm install

Inicie o servidor de desenvolvimento:

ng serve

O aplicativo estará disponível em http://localhost:4200.

🔗 Conectando com a API
Este frontend se conecta a uma API. A URL base da API é configurada no arquivo src/environments/environment.ts. Se você precisar mudar o endereço do backend, é só editar lá.

apiUrl: 'http://localhost:8000/api'