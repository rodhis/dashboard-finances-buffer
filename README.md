# Dashboard Finances Buffer

![image](https://github.com/user-attachments/assets/8827329c-fc35-4c7b-878e-62918a9a8add)

[https://www.figma.com/design/Q44nlEVrODE7W6iBFRVPZL/Desafio-para-devs---App-%2F-Dashboard-%7C-UX%2FUI?node-id=13-5855&t=tUBMBPpD27NQIcDo-0](https://www.figma.com/design/Q44nlEVrODE7W6iBFRVPZL/Desafio-para-devs---App-%2F-Dashboard-%7C-UX%2FUI?node-id=13-5855&t=tUBMBPpD27NQIcDo-0)

### 🚀 Features

✅ Arquitetura atômica (Atoms, Molecules, Organisms)

✅ Login

✅ Cadastro

✅ Editor de Perfil

✅ Visualizador de Statements / Operações

✅ Filtro de Busca

✅ Modo Escuro

### ☂️ Frameworks & Libraries

Vite - Ferramenta de gerenciamento de pacotes e criação de projetos.

React → Lib/framework para desenvolvimento do projeto.

React-Router-DOM → Lib para roteamento de páginas em SPAs (Single-Page Applications).

React-Hook-Form → Criação mais fácil de formulários compatíveis com React.

Typescript → Fornece suporte forte a tipos e debug pré-produção.

JSON-server → Muito útil para simular um back-end que aceita entradas JSON.

ZOD → Lib para validação de formulários.

BaseUI → Variação simples da MaterialUI que fornece componentes pré-prontos e facilita implementação de acessibilidade.

Tailwind → Framework de CSS que agiliza a estilização através de personalização por tag.

Storybook → Para criação e visualização de documentações para cada componente.

Cypress → Para testes conectados.

Vitest e React-Testing-Library → Para testes por componente.


### 🚩 Husky

Para evitar commits problemáticos, utilizamos a lib Husky para implementar verificações pré-commit e pré-push, abaixo estão os scripts que rodam conforme comando realizado.

scripts pre-commit:

```jsx
npx lint-staged
```

scripts pré-push

```jsx
npm run test
```

### 🔨 Build

```jsx
# Clone este repositório
$ git clone https://github.com/PB-Imortal/dashboard-finances-buffer.git

# Acesse a pasta do projeto no terminal/cmd
$ cd ./dashboard-finances-buffer/

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# Execute o servidor da aplicação num terminal à parte
$ npm run server

# O servidor inciará tipicamente na porta:5173
```
