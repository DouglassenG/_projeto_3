# 🚀 Landing Page Institucional

![Project Status](https://img.shields.io/badge/Status-Finalizado-green)
![React](https://img.shields.io/badge/React-18-blue?logo=react)
![CSS3](https://img.shields.io/badge/Styling-CSS_Modules-1572B6?logo=css3)
![Responsiveness](https://img.shields.io/badge/Design-Mobile_First-orange)

> Um projeto de interface web focado na fidelidade visual e na experiência do usuário em múltiplos dispositivos.

## 🎯 Motivação e Propósito

Este projeto foi desenvolvido com o objetivo de solidificar os fundamentos de **Front-end UI**. Diferente de aplicações focadas em lógica de dados, o propósito aqui é resolver desafios de **Layout e Apresentação**.

A motivação principal foi criar uma Landing Page que fosse não apenas funcional, mas esteticamente agradável e tecnicamente otimizada, demonstrando a capacidade de transformar um protótipo de design em código limpo, semântico e escalável. Ele resolve o problema de apresentação institucional de uma marca ou evento.

## 🖼️ Demonstração Visual

https://projeto-3-orcin-delta.vercel.app/

## 🛠️ Tecnologias Utilizadas

A construção da interface utilizou uma stack voltada para componentização e manutenibilidade de estilos:

* **[React.js](https://reactjs.org/):** Biblioteca principal para a estruturação da UI em componentes reutilizáveis.
* **CSS (Modules ou Styled Components):** Utilizado para estilização escopada, garantindo que não haja conflitos de classes e facilitando a manutenção.
* **Media Queries:** Implementação de breakpoints manuais para garantir responsividade em Mobile, Tablet e Desktop.
* **NPM/Yarn:** Gerenciamento de dependências e scripts de automação.

## 📦 Instalação

Siga o passo a passo abaixo para configurar o ambiente de desenvolvimento em sua máquina.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/DouglassenG/_projeto_3.git](https://github.com/DouglassenG/_projeto_3.git)
    ```

2.  **Acesse o diretório do projeto:**
    ```bash
    cd _projeto_3
    ```

3.  **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

4.  **Execute o projeto:**
    ```bash
    npm start
    # ou
    yarn start
    ```

O aplicativo será aberto no modo de desenvolvimento em [http://localhost:3000](http://localhost:3000).

## 💻 Uso e Exemplos

O projeto é estruturado em seções modulares. A estrutura de pastas reflete a separação de responsabilidades visuais:

```text
src/
├── components/      # Componentes isolados (Botões, Cards, Inputs)
├── sections/        # Seções da Landing Page (Hero, Sobre, Contato)
├── assets/          # Imagens, fontes e vetores
├── styles/          # Configurações globais de CSS (Variáveis, Reset)
└── App.js           # Ponto de entrada da interface
