# 🎬 Projeto Spring-React - DSMovie

Este é um projeto simples de um sistema de avaliação de filmes, desenvolvido com **ReactJS** no frontend e **Spring Boot** no backend. O objetivo do sistema é permitir que os usuários consultem filmes e atribuam notas para cada um deles.

## 🛠 Tecnologias Utilizadas

### Frontend (ReactJS):
- ⚛️ **ReactJS** - Biblioteca para construção da interface
- 🎨 **CSS** - Estilização da aplicação
- 🔗 **React Router** - Navegação entre páginas
- 🌟 **Axios** - Comunicação com a API

### Backend (Spring Boot):
- ☕ **Java** - Linguagem de programação
- 🎯 **Spring Boot** - Framework para API REST
- 🏦 **Spring Data JPA** - Gerenciamento do banco de dados
- 🗄 **H2 Database / PostgreSQL** - Banco de dados
- 🔐 **Spring Security** - Configuração de segurança básica

## 📂 Estrutura do Projeto

### Backend (`/backend/src/main/java/com/devsuperior/dsmovie`)
- `controllers/` - Controladores REST
- `dto/` - Objetos de Transferência de Dados
- `entities/` - Modelos de entidades
- `repositories/` - Interfaces para acesso ao banco de dados
- `services/` - Regras de negócio
- `config/` - Configurações de segurança e do sistema

### Frontend (`/frontend/src`)
- `components/` - Componentes reutilizáveis (ex.: MovieCard, MovieScore, Navbar)
- `pages/` - Páginas principais da aplicação (ex.: Form, Listing)

## 🚀 Como Executar o Projeto

### 🎲 Backend:
1. Acesse a pasta do backend: `cd backend`
2. Execute o projeto com o Spring Boot: `./mvnw spring-boot:run`

### 🎨 Frontend:
1. Acesse a pasta do frontend: `cd frontend`
2. Instale as dependências: `npm install`
3. Inicie o React: `npm start`

## 📌 Funcionalidades
✅ Listagem de filmes
✅ Paginação de resultados
✅ Atribuição de notas aos filmes
✅ Atualização da média das avaliações

## 📜 Licença
Este projeto está sob a licença MIT. Sinta-se livre para utilizá-lo e modificá-lo conforme necessário! 🎉

---

Feito com ❤️ por [João Batista] 🚀

