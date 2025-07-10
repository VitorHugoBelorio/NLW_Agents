# NLW Agents

Projeto desenvolvido durante o evento da Rocketseat.

## Tecnologias Utilizadas

- **React 19** (SPA)
- **Vite** (bundler e dev server)
- **TypeScript**
- **React Router DOM** (rotas)
- **@tanstack/react-query** (cache e dados assíncronos)
- **TailwindCSS** (estilização)
- **class-variance-authority, clsx, tailwind-merge** (utilitários de classes)
- **Radix UI** (componentes acessíveis)
- **Lucide React** (ícones SVG)
- **Fastify** (API backend)
- **Drizzle ORM** (ORM para PostgreSQL)
- **Zod** (validação de schemas)
- **PostgreSQL** (banco de dados)

## Padrões de Projeto

- Componentização em `src/components`
- Páginas em `src/pages`
- Hooks e Providers para dados assíncronos
- Alias `@` para importações de `src`

## Setup e Configuração

1. **Clone o repositório**

   ```sh
   git clone <https://github.com/VitorHugoBelorio/NLW_Agents.git>
   cd NLW_Agents
   ```

2. **Configuração do Backend**

   ```sh
   cd server
   cp .env.example .env
   # Edite o arquivo .env conforme necessário (ex: credenciais do banco)
   npm install
   npm run db:seed # Popula o banco de dados (opcional)
   npm run dev     # Inicia o servidor Fastify
   ```

3. **Configuração do Frontend**
   ```sh
   cd web
   npm install
   npm run dev     # Inicia o Vite
   ```

Acesse a aplicação em `http://localhost:5173` (frontend) e `http://localhost:3333` (backend).
