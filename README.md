# 🧩 Frontend - Projeto NLW Agents

Este repositório contém o **frontend** da aplicação NLW Agents, desenvolvido com **React**, **TypeScript**, **Vite** e **TailwindCSS**.  
Ele consome a API do backend hospedado no repositório [`nlwAgents_backend`](https://github.com/bruno-lippert/nlwAgents_backend).

---

## 🛠️ Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Zod](https://github.com/colinhacks/zod)
- [React Hook Form](https://react-hook-form.com/)
- [Shadcn UI](https://ui.shadcn.com/)

---

## 📦 Instalação

### 1. Clone o projeto

```bash
git clone https://github.com/bruno-lippert/nlwAgents_fontend.git
cd nlwAgents_fontend
```

### 2. Instale as dependências

```bash
# Para instalar as dependecias
npm install
```

#### 🚀 Executando o Projeto

```bash
npm run dev

Abra o navegador e acesse: http://localhost:5173
```

#### 🧪 Scripts úteis
```bash
# Rodar em modo desenvolvimento
npm run dev

# Build para produção
npm run build

# Visualizar o build localmente
npm run preview

```


#### 📁 Estrutura do Projeto
```bash
src/
├── components/       # Componentes reutilizáveis
        ├──ui         # Componentes shadcn
├── pages/            # Páginas da aplicação
├── lib/              # Funções utilitárias
├── App.tsx           # Componente raiz
└── main.tsx          # Ponto de entrada do React

```

#### 📎 Observações
Este projeto depende do backend: [nlwAgents_backend](https://github.com/bruno-lippert/nlwAgents_backend)