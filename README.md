# 🛒 Digital Store

Uma aplicação Full Stack de e-commerce construída com rigor técnico, visando performance, tipagem estática e escalabilidade.

## 🚀 Arquitetura e Decisões Técnicas

Este projeto foi arquitetado unificando o ecossistema Frontend e Backend através do **Next.js**, garantindo tipagem de ponta a ponta com **TypeScript**. 

* **Frontend:** React + Next.js (App Router), focado em componentes reutilizáveis (Dumb Components) e modularização de CSS.
* **Backend:** API RESTful construída em Node.js.
* **Banco de Dados:** MySQL para persistência relacional.
* **Segurança:** Autenticação baseada em JWT (JSON Web Tokens).
* **Qualidade:** Código padronizado com ESLint/Prettier e testado com Jest.

## ⚙️ Funcionalidades Core

### 🛍️ Frontend (Store)
- Listagem dinâmica de produtos com grid responsivo.
- Sistema avançado de filtros (Categorias, Preço, Opções).
- Galeria de imagens interativa (Carrossel e Thumbnails).
- Carrinho de compras com estado global.

### 🛡️ Backend (API)
- CRUD completo e paginado de Produtos e Categorias.
- Gestão de Usuários com senhas criptografadas (Bcrypt).
- Proteção de rotas sensíveis via Middleware JWT.
- Banco de dados relacional (Sequelize ORM).

## 🛠️ Instalação e Execução Local

### Pré-requisitos
- Node.js (v18+)
- MySQL (rodando localmente ou via Docker)

### Passo a Passo

1. **Clone o repositório**
   ```bash
   git clone [https://github.com/seu-usuario/digital-store.git](https://github.com/seu-usuario/digital-store.git)
   cd digital-store
