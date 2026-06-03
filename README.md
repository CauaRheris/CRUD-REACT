# CS Market - Sistema de E-Commerce com CRUD Dinâmico

O **CS Market** é uma aplicação Single Page Application (SPA) desenvolvida em **React.JS** com **Vite** para a segunda entrega da disciplina de Programação Web. O sistema evoluiu de uma vitrine estática para um ecossistema completo e reativo que integra a experiência do cliente e um Painel Administrativo gerencial (CRUD).

## 🎯 Objetivo do Sistema
Atender aos requisitos de manipulação de estado em memória do React, permitindo realizar as quatro operações fundamentais de dados (**C**reate, **R**ead, **U**pdate, **D**elete) sobre o inventário de produtos da loja (eletrônicos, periféricos e hardware), mantendo a fidelidade visual, responsividade e paleta de cores corporativa da entrega anterior.

## ✨ Funcionalidades Implementadas
* **Vitrine do Cliente (Read):** Renderização dinâmica dos 15 produtos originais com sistema de avaliação por estrelas, descrições detalhadas e preços formatados.
* **Carrinho de Compras Reativo:** Adição de itens com controle de quantidade acumulada. O carrinho calcula dinamicamente o subtotal dos produtos, aplica a taxa de frete estimada e atualiza o valor total em tempo real ao aumentar ou diminuir unidades.
* **Painel Administrativo Protegido:** Interface gerencial acessível por botão exclusivo para inserção, edição rápida e exclusão definitiva de produtos do catálogo.
* **Upload de Imagens via Anexo:** Integração com a API `FileReader` do navegador para conversão de imagens locais anexadas pelo usuário em strings *Base64*, permitindo o cadastro de novos itens com fotos personalizadas sem necessidade de backend.
* **Pré-visualização em Tempo Real (Preview):** Layout dividido (*Split Layout*) no formulário que renderiza o card do produto de forma instantânea conforme os campos são preenchidos.

## 🛠️ Tecnologias Utilizadas
* **ReactJS** (Hooks: `useState`, `useEffect`)
* **Vite** (Ferramental de build rápido)
* **JavaScript (ES6+)**
* **CSS3** (Estilização avançada e Media Queries para responsividade)
* **Bootstrap Icons** (Biblioteca de vetores para interface)

## 🚀 Como Executar o Projeto Localmente

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina antes de prosseguir.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
    ```
2.  **Acesse a pasta raiz do projeto:**
    ```bash
    cd Trabalho_DevWeb
    ```
3.  **Instale as dependências do npm:**
    ```bash
    npm install
    ```
4.  **Inicie o servidor de desenvolvimento local:**
    ```bash
    npm run dev
    ```
5.  Abra o navegador e acesse o endereço local fornecido no terminal (geralmente `http://localhost:5173`).

## 👥 Desenvolvedores
* **Sandro Hugo** - *sandrohugols.05@gmail.com*
* **Cauã Rheris** - *crheris@gmail.com*
