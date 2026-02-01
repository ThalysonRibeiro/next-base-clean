# 🚀 Next.js Clean Template

Um template **clean** e minimalista do Next.js — ideal para iniciar novos projetos com uma base consistente e organizada.

## 🧱 Estrutura do projeto

```
.
├── src/
│   ├── app/               # Estrutura App Router do Next.js
│   ├── components/        # Componentes reutilizáveis
│   ├── lib/               # Funções helpers e utilitárias
│   ├── styles/            # Estilos globais (Tailwind ou CSS)
│   └── types/             # Tipos TypeScript globais
│
├── .eslintrc.json         # Configuração do ESLint
├── .prettierrc            # Configuração do Prettier
├── .prettierignore         # Arquivos ignorados pelo Prettier
├── tsconfig.json           # Configuração do TypeScript
├── package.json
└── README.md
```

---

## ⚙️ Tecnologias incluídas

- 🟦 **Next.js** (versão mais recente)
- ⚡ **TypeScript**
- 💅 **Prettier** — formatação de código automática
- 🧹 **ESLint** — análise estática e boas práticas
- 🎨 **Tailwind CSS** (opcional)

---

## 🧰 Como usar este template

### 1️⃣ Criar novo projeto a partir deste template

```bash
npx create-next-app@latest -e https://github.com/ThalysonRibeiro/next-base-clean nome-do-projeto
```

ou com **pnpm**:

```bash
pnpm create next-app -e https://github.com/ThalysonRibeiro/nextjs-clean nome-do-projeto
```

---

### 2️⃣ Instalar dependências

```bash
npm install
# ou
pnpm install
# ou
yarn install
```

---

### 3️⃣ Rodar o projeto

```bash
npm run dev
# ou
pnpm dev
# ou
yarn dev
```

O servidor será iniciado em `http://localhost:3000`.

---

## 🎯 Padrões de código

O template já vem configurado para funcionar com **Prettier + ESLint**.  
O VSCode irá formatar automaticamente os arquivos ao salvar.

### `.prettierrc`
```json
{
  "semi": false,
  "singleQuote": true,
  "tabWidth": 2,
  "trailingComma": "none",
  "printWidth": 100
}
```

### `.prettierignore`
```
node_modules
.next
dist
build
coverage
```

---

## 🧩 Sugestão de extensões do VSCode

| Extensão | ID |
|-----------|--------------------------------|
| Prettier | `esbenp.prettier-vscode` |
| Tailwind CSS IntelliSense | `bradlc.vscode-tailwindcss` |
| ESLint | `dbaeumer.vscode-eslint` |

---

## 💡 Dica

Se o Prettier não estiver formatando automaticamente, verifique no VSCode:
1. O Prettier está instalado (`esbenp.prettier-vscode`)?  
2. O arquivo `.prettierrc` existe na raiz do projeto?  
3. `"editor.formatOnSave": true` está ativo nas configurações?  

---

## 📄 Licença

Este projeto está sob a licença MIT — sinta-se livre para usar e modificar.

---

Feito com ❤️ por [Seu Nome]
