# Job Finder

**Job Finder** é uma aplicação web desenvolvida para ajudar pessoas a encontrar oportunidades de emprego, com foco especial em vagas na área de tecnologia e com a possibilidade de home office.

## 📑 Funcionalidades

- **Ver Vagas**: Os usuários podem visualizar as vagas disponíveis e filtrar as oportunidades de acordo com as suas preferências.
- **Abrir Vagas**: Empresas podem cadastrar novas vagas através de um formulário simples e intuitivo.
- **Busca de Vagas**: É possível buscar vagas específicas por meio de um campo de busca.
- **Vagas Home Office**: O projeto prioriza vagas remotas para atender a demanda crescente por trabalho em casa.

## 🚀 Tecnologias Utilizadas

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Node.js, Express.js
- **Templating Engine**: Handlebars.js
- **Banco de Dados**: Sequelize (ORM) com MySQL
- **Controle de Versionamento**: Git e GitHub

## 📂 Estrutura do Projeto

job_finder/ ├── views/ # Páginas e templates em Handlebars │ ├── layouts/ # Layouts principais do site │ ├── partials/ # Componentes reutilizáveis │ └── index.handlebars # Página principal ├── public/ # Arquivos estáticos (CSS, JS, imagens) ├── routes/ # Definição das rotas (endpoints da API) ├── models/ # Modelos do Sequelize para o banco de dados ├── db/ # Conexão e configuração do banco de dados ├── .gitignore # Arquivos e pastas ignoradas pelo Git ├── app.js # Arquivo principal da aplicação (inicializa o servidor) ├── package.json # Configurações e dependências do projeto └── README.md # Documentação do projeto


## 🛠️ Instalação e Configuração

Siga os passos abaixo para rodar o projeto localmente:

1. Clone o repositório:
   ```bash
   git clone https://github.com/pedropetali1/job_finder.git
2. Navegue até o diretório do projeto:
   cd job_finder
3. Instale as dependências:
   npm install
4. Crie e configure o arquivo .env com as credenciais do banco de dados.
5. Execute a migração do banco de dados:
   npx sequelize db:migrate
6. Inicie o servidor:
   npm start
7. Acesse a aplicação no navegador através de http://localhost:3000.

## 📚 Documentação da API

Método	Rota	Descrição
GET	/jobs	Lista todas as vagas cadastradas
GET	/jobs/:id	Exibe detalhes de uma vaga
POST	/jobs	Cadastra uma nova vaga
DELETE	/jobs/:id	Exclui uma vaga

🖼️ Layout

O layout da aplicação é construído usando Bootstrap, tornando-o responsivo e acessível tanto em dispositivos móveis quanto em desktops.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues para melhorias e correções.
   
