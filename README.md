# 🤖 NLW Agents

<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E" alt="Vite"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=tanstack&logoColor=white" alt="TanStack Query"/>
</div>

> Uma aplicação moderna de perguntas e respostas com IA desenvolvida durante a trilha avançada do Next Level Week (NLW) da Rocketseat.

## 📋 Sobre o Projeto

O NLW Agents é uma plataforma interativa que permite aos usuários criar salas de perguntas e respostas, onde podem fazer perguntas por texto ou áudio e receber respostas geradas por Inteligência Artificial. A aplicação foi construída com foco em performance, usabilidade e experiência do usuário.

### 🎯 Funcionalidades

- ✅ Criação e gerenciamento de salas
- ✅ Perguntas por texto e áudio
- ✅ Respostas geradas por IA
- ✅ Interface responsiva e acessível
- ✅ Tempo real e sincronização de dados

## 🛠️ Stack Tecnológica

### Core

- **[React](https://react.dev/)** - Biblioteca para construção de interfaces
- **[Vite](https://vitejs.dev/)** - Ferramenta de build rápida e moderna
- **[TypeScript](https://www.typescriptlang.org/)** - Superset tipado do JavaScript

### Roteamento & Estado

- **[React Router DOM](https://reactrouter.com/)** - Roteamento declarativo
- **[TanStack Query](https://tanstack.com/query/latest)** - Gerenciamento de estado do servidor

### Formulários & Validação

- **[React Hook Form](https://react-hook-form.com/)** - Formulários performáticos
- **[Zod](https://zod.dev/)** - Validação de esquemas TypeScript-first

### Interface & Estilização

- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utilitário
- **[shadcn/ui](https://ui.shadcn.com/)** - Componentes de UI acessíveis
- **[Lucide React](https://lucide.dev/)** - Biblioteca de ícones

### Utilitários

- **[Day.js](https://day.js.org/)** - Manipulação de datas
- **[Biome](https://biomejs.dev/)** - Linting e formatação de código

## 🏗️ Arquitetura do Projeto

### Estrutura de Diretórios

```
src/
├── components/          # Componentes reutilizáveis
│   ├── ui/             # Componentes base (shadcn/ui)
│   └── ...             # Componentes customizados
├── pages/              # Páginas da aplicação
├── hooks/              # Custom hooks
├── lib/                # Utilitários e configurações
└── types/              # Definições de tipos TypeScript
```

### Padrões Arquiteturais

**🧩 Componentes Atômicos**

- Separação clara entre componentes de UI base e específicos
- Reutilização através de `shadcn/ui`
- Composição de interfaces complexas

**🔄 Data Fetching**

- Custom hooks para abstração da API
- Cache inteligente com TanStack Query
- Gerenciamento automático de loading e erro

**📝 Validação Robusta**

- Esquemas Zod para validação de dados
- Integração com React Hook Form
- Tipagem forte end-to-end

**🎛️ Gerenciamento de Estado**

- Estado do servidor via TanStack Query
- Estado local com hooks nativos do React
- Sincronização automática de dados

## 🚀 Configuração e Execução

### Pré-requisitos

- **Node.js** 18+
- **npm**, **yarn** ou **pnpm**
- **Servidor backend** rodando na porta 3333

### Instalação

1. **Clone o repositório**

   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_DIRETORIO_DO_PROJETO>
   ```

2. **Instale as dependências**

   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**

   ```bash
   npm run dev
   ```

4. **Acesse a aplicação**
   ```
   http://localhost:5173
   ```

## ⚙️ Configuração

### Variáveis de Ambiente

O projeto está configurado para se comunicar com a API em `http://localhost:3333`. Certifique-se de que o servidor backend esteja rodando neste endereço.

### Requisitos do Backend

- Servidor rodando na porta **3333**
- Endpoints compatíveis com a API esperada
- Suporte a WebSocket (se aplicável)

<div align="center">
  <p>Desenvolvido com 💜 durante o <strong>Next Level Week</strong> da <a href="https://rocketseat.com.br">Rocketseat</a></p>
</div>
