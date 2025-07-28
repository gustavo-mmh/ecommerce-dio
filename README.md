# ⚽ Soccer Shop E-commerce com React e Redux

Este projeto é uma aplicação de e-commerce front-end desenvolvida com React e Redux, focada na venda de produtos relacionados a futebol, como camisas de times e seleções. A loja possui um catálogo de produtos, funcionalidade de carrinho de compras e gerenciamento de estado centralizado para uma experiência de usuário fluida e eficiente.

## ✨ Funcionalidades

  * **Catálogo de Produtos:** 👕 Exibe uma lista de produtos de futebol com imagens e informações detalhadas.
  * **Carrinho de Compras:** 🛒 Permite adicionar produtos ao carrinho, visualizar os itens selecionados e o total da compra.
  * **Gerenciamento de Estado:** ⚛️ Utiliza Redux para um gerenciamento de estado global e previsível de produtos e do carrinho de compras.
  * **Navegação entre Páginas:** ➡️ Roteamento configurado para navegar entre a página inicial (catálogo de produtos) e uma página de contato.
  * **Componentes Reutilizáveis:** 🧩 A aplicação é construída com uma arquitetura modular, utilizando componentes React para exibir produtos (Card, Item) e o carrinho (Cart).
  * **Design Intuitivo:** Interface clara e fácil de usar para o cliente.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído com as seguintes tecnologias principais:

  * **React:** Biblioteca JavaScript para a construção da interface de usuário.
  * **Redux:** Para gerenciamento centralizado do estado da aplicação.
  * **React Redux:** Integração do Redux com o React, permitindo que os componentes se conectem ao estado da store Redux.
  * **React Router DOM:** Para roteamento no lado do cliente, gerenciando a navegação entre as páginas.
  * **JavaScript (ES6+):** Lógica da aplicação.
  * **CSS:** Para estilização e layout dos componentes.

## 📂 Estrutura do Projeto

A estrutura de diretórios do projeto é organizada da seguinte forma:

```
├── public/                     # Arquivos públicos (HTML, imagens de produtos, ícones) 🌐
│   ├── favicon.ico
│   ├── index.html              # Arquivo HTML principal da aplicação
│   ├── images/                 # Imagens gerais e de produtos (camisas de times) 🖼️
│   └── ...
├── src/                        # Código-fonte da aplicação 💻
│   ├── App.js                  # Componente principal da aplicação
│   ├── Pages/                  # Páginas da aplicação (home, contato) 📄
│   │   ├── contato.js
│   │   └── home.js
│   ├── components/             # Componentes de UI reutilizáveis (Card, Header, Item, Cart) 🧩
│   │   ├── Card.js
│   │   ├── Cart/
│   │   ├── Header.js
│   │   └── Item.js
│   ├── components/store/       # Configuração e lógica do Redux 📦
│   │   ├── actions/cart.js     # Ações do carrinho
│   │   ├── reducers/           # Reducers (cart, product, products)
│   │   └── index.js            # Store Redux
│   ├── index.js                # Ponto de entrada da aplicação React
│   └── routes.js               # Definição das rotas da aplicação 🗺️
├── package.json                # Dependências do projeto e scripts 📋
├── package-lock.json           # Bloqueio de versões de dependências 🔒
└── .gitignore                  # Arquivos e diretórios a serem ignorados pelo Git 🚫
```

## 🚀 Como Começar

Siga estas instruções para obter uma cópia do projeto em execução em sua máquina local.

### 📋 Pré-requisitos

  * **Node.js:** Certifique-se de ter o Node.js instalado (inclui npm).
  * **npm** (Node Package Manager) ou **Yarn**.

### ⬇️ Instalação

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd ecommerce-dio
    ```
2.  **Instale as dependências:**
    Usando npm:
    ```bash
    npm install
    ```
    Ou usando Yarn:
    ```bash
    yarn install
    ```

### ▶️ Executando a Aplicação

Para iniciar o servidor de desenvolvimento:

```bash
npm start
# ou
yarn start
```

Isso abrirá o aplicativo em seu navegador padrão em `http://localhost:3000`. A página será automaticamente recarregada quando você fizer alterações no código.

## 📜 Scripts Disponíveis

No diretório do projeto, você pode executar:

  * **`npm start`**: 🚀 Inicia o aplicativo em modo de desenvolvimento.
  * **`npm test`**: 🧪 Inicia o executor de testes em modo de observação interativo.
  * **`npm run build`**: 🏗️ Compila o aplicativo para produção na pasta `build`.
  * **`npm run eject`**: Remove a dependência única de build do seu projeto. **Use com cautela, esta operação é irreversível\!**

## 🤝 Contribuição

Contribuições são bem-vindas\! Se você tiver sugestões, melhorias ou encontrar bugs, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## ⚖️ Licença

Este projeto é de código aberto.
