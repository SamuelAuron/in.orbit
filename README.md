<img src="https://github.com/SamuelAuron/assets/blob/main/in-orbit/Thumbnail.png" />

<p align="center">
  <img src="https://img.shields.io/badge/react-17.0.2-informational"/>
  <img src="https://img.shields.io/badge/next-10.1.3-important" />
  <img src="https://img.shields.io/badge/license-MIT-success"/>
</p>

<p align="center">
  <a href="#-features">Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-pré-requisitos">Pré-Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Lincença</a>
</p>

### 📎 Features 

- [x] Cadastrar metas
- [x] Visualizar metas da semana
- [x] Barra de progresso das metas da semana
- [x] Marcar meta como concluida
- [ ] Remover meta
- [ ] Remover meta concluida
- [ ] Autenticação de usuários via Google/Github;
- [ ] Navegação entre semanas para visualizar metas passadas;
- [ ] Botões de “próxima” e “anterior” para navegação;
- [ ] Gráficos de performance semanal e mensal;

### 💻 Projeto

O In.orbit é uma aplicação para registro de metas semanais. Nele é possivel cadastrar novas metas, marcar metas como conluidas e acompanhar quanto falta para concluir todas as metas da semana.

### ✅ Demonstração
<p >
  <img src="https://github.com/SamuelAuron/assets/blob/main/in-orbit/Create%20goal.png" height="300" />
  <img src="https://github.com/SamuelAuron/assets/blob/main/in-orbit/Goals.png" height="300" />
</p>


### ⚙ Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [Yarn](https://yarnpkg.com/) e [Docker](https://www.docker.com/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 📗 Rodando a Aplicação (server)

```bash
# Clone este repositório
$ git clone https://github.com/SamuelAuron/in.orbit.git

# Entre na pasta server

# Instale as dependências
$ npm i

# É necessário ter o docker instalado para executar o próximo passo
# Inicialize os containers
$ docker compose up -d

# Execute as migrates
$ npx drizzle-kit migrate

# Opcional!
# Insira algumas atividades no banco de dados
$ npm run seed

# Executa o server
$ npm run dev

```


### 📗 Rodando a Aplicação (web)

```bash
# Clone este repositório
$ git clone https://github.com/SamuelAuron/in.orbit.git

# Entre na pasta web

# Instale as dependências
$ npm i

# Execute a aplicação
$ npm run dev

```

### 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- Vite
- React
- Typescript
- Node
- Docker
- Fastify
- Tailwind CSS
- Radix-ui

### 📕 Bibliotecas

Esse projeto foi utilizou das seguintes lib:
- React-hook-form
- Dayjs
- Postgres
- Zod
- Biome
- Drizzle-orm
- Lucide-react


### 📝 Licença

Esse projeto está sob a licença MIT.

<hr/>

Feito por Samuel Dutra
