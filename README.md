# Gerenciamento de Usuários - CRUD Full Stack

Este projeto é uma aplicação de gerenciamento de usuários, utilizando uma stack **Full Stack CRUD** com **Node.js**, **React** e **MySQL**. A aplicação permite adicionar, editar, visualizar e excluir usuários em uma interface simples e funcional.

## Tecnologias Utilizadas

- **Node.js**: Para o backend, responsável pelo gerenciamento das requisições HTTP e integração com o banco de dados.
- **React**: Para a interface do usuário, utilizando componentes funcionais e hooks.
- **MySQL**: Banco de dados relacional para armazenar as informações dos usuários.
- **Axios**: Cliente HTTP usado no frontend para realizar requisições ao backend.
- **React-toastify**: Biblioteca para exibição de notificações de sucesso ou erro.

## Como baixar e executar o projeto

Siga os passos abaixo para clonar e rodar o projeto localmente.

### 1. Clone o repositório

Use o comando abaixo para clonar o repositório:

```bash
git clone https://github.com/seuusuario/seuprojeto.git
```

Substitua `seuusuario` e `seuprojeto` pela URL correta do repositório.

### 2. Acesse o diretório do projeto

Navegue até a pasta do projeto:

```bash
cd seuprojeto
```

### 3. Instale as dependências do frontend

Execute o seguinte comando para instalar as dependências necessárias no frontend:

```bash
npm install
```

ou, se você estiver usando `yarn`:

```bash
yarn install
```

### 4. Configurar o Backend

- Navegue até a pasta do backend (geralmente algo como `server` ou `backend`):

```bash
cd backend
```

- Instale as dependências do backend:

```bash
npm install
```

- Configure o banco de dados MySQL criando uma base de dados e ajustando as credenciais no arquivo de configuração do backend (geralmente `.env` ou no arquivo de configuração principal do Node.js).

- Inicie o servidor backend:

```bash
npm start
```

### 5. Execute o Frontend

No diretório raiz do projeto (onde está o código do React), inicie o servidor de desenvolvimento:

```bash
npm run dev
```

ou

```bash
yarn dev
```

### 6. Acesse a aplicação

Abra o navegador e acesse:

```bash
http://localhost:3000
```

Agora você poderá usar a aplicação de gerenciamento de usuários, com todas as funcionalidades de CRUD integradas com o backend em **Node.js** e o banco de dados **MySQL**.

### Estrutura do Projeto

- **Frontend (React)**:
  - `App.js`: Componente principal que carrega o formulário de usuário e a grid que exibe os usuários.
  - `Form.js`: Componente responsável pelo formulário de cadastro/edição de usuários.
  - `Grid.js`: Componente responsável por exibir os usuários em uma tabela.
  - `global.js`: Estilizações globais aplicadas à aplicação.
  
- **Backend (Node.js & MySQL)**:
  - `server.js`: Arquivo principal do servidor.
  - `routes/`: Contém as rotas que lidam com as operações CRUD.
  - `controllers/`: Lógica de negócios para interação com o banco de dados.
  - `models/`: Define os modelos de dados usados no banco MySQL.


