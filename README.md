# 🎬 MovieCity — Landing Page de Filmes

## 📌 Sobre o projeto

O **MovieCity** é uma landing page responsiva de uma plataforma fictícia de streaming de filmes, desenvolvida utilizando React e Vite. O projeto tem como objetivo praticar o desenvolvimento de interfaces web, a componentização com React e a estilização utilizando CSS puro.

A página apresenta um layout moderno, com um cabeçalho de navegação e uma área principal contendo cards com imagens de filmes.

## 🎯 Funcionalidades

- **Cabeçalho (Header):** exibe a logo MovieCity, os links de navegação e o botão de Login.
- **Área principal (Main):** apresenta o título "Seus Filmes", um texto de destaque e um botão "Mais".
- **Cards de filmes:** exibe seis filmes com imagens ilustrativas:
  - Afterlife
  - Transformers
  - Mowgli
  - Shift
  - Round 6 (Squid Game)
  - Harry Potter
- **Menu responsivo:** em telas menores, a navegação se transforma em um menu hambúrguer que pode ser aberto e fechado.
- **Layout adaptável:** organiza o conteúdo de acordo com o tamanho da tela, proporcionando uma melhor experiência em computadores e dispositivos móveis.

## 🛠️ Tecnologias utilizadas

- **React 19:** biblioteca JavaScript utilizada para construir interfaces por meio de componentes.
- **Vite 7:** ferramenta utilizada para criar e executar o projeto React, oferecendo um servidor de desenvolvimento rápido.
- **JavaScript (ES6+):** linguagem utilizada para implementar a lógica e a interação da aplicação.
- **CSS3:** utilizado para estilização, organização dos elementos, cores, espaçamentos e responsividade.
- **HTML5:** estrutura base da aplicação web.
- **ESLint:** ferramenta utilizada para identificar possíveis problemas e manter a padronização do código.

## 📱 Responsividade

O projeto utiliza CSS e media queries para adaptar a interface a diferentes tamanhos de tela.

Em dispositivos menores:
- O conteúdo principal passa a ser organizado em colunas empilhadas.
- Os cards de filmes são distribuídos em duas colunas.
- O menu de navegação é substituído por um menu hambúrguer.

## 📂 Estrutura do projeto

A estrutura sugerida para a aplicação é:

```text
01_landinpage/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Main.jsx
│   │   └── Home.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
```

**Principais arquivos:**

- `App.jsx`: componente principal da aplicação.
- `Home.jsx`: organiza o cabeçalho e o conteúdo principal.
- `Header.jsx`: responsável pelo cabeçalho e pela navegação.
- `Main.jsx`: responsável pela área principal e pela apresentação dos filmes.
- `index.css`: contém as regras de estilização e responsividade.
- `main.jsx`: inicializa a aplicação React.

*Observação: a estrutura acima é uma referência baseada no roteiro do projeto. Os nomes e a organização devem corresponder aos arquivos existentes na versão final do código.*

## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, é necessário ter instalado:

- Node.js 20.19+ ou 22.12+.
- npm, instalado junto com o Node.js.
- Visual Studio Code ou outro editor de código.

### Passo a passo

**1. Abra o terminal na pasta do projeto.**

**2. Instale as dependências:**

```bash
npm install
```

**3. Execute o servidor de desenvolvimento:**

```bash
npm run dev
```

**4. Acesse a aplicação** pelo endereço exibido no terminal. Normalmente:

```text
http://localhost:5173
```

Para encerrar o servidor, pressione `Ctrl + C` no terminal.

## 📚 Objetivo educacional

Este projeto foi desenvolvido com o objetivo de aplicar conhecimentos de desenvolvimento front-end, explorando a criação de componentes reutilizáveis, a organização de arquivos, a utilização de estados no React e a construção de layouts responsivos com CSS.

A atividade também contribui para o aprendizado da estruturação de projetos com Vite e da identificação de possíveis problemas no código utilizando o ESLint.

## 🔮 Melhorias futuras

- Implementar a navegação entre páginas.
- Adicionar filtros por gênero e categoria.
- Criar uma funcionalidade de pesquisa de filmes.
- Implementar autenticação de usuários.
- Integrar uma API para obter informações atualizadas sobre filmes.
- Melhorar as interações dos botões e dos cards.

---

**Projeto educacional — Desenvolvimento Web com React.**
