# 🚀 Landing Page Institucional (Projeto 3)

![Project Status](https://img.shields.io/badge/Status-Finalizado-green)
![React](https://img.shields.io/badge/React-18.2-blue?logo=react)
![CSS3](https://img.shields.io/badge/Style-CSS_Modules%2FStyled-db7093?logo=css3)
![Responsiveness](https://img.shields.io/badge/Design-Responsive-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

> Um projeto de interface web focado na fidelidade visual (Pixel Perfect) e na adaptabilidade de layout para múltiplos dispositivos.

## 🔭 Motivação e Propósito

Este projeto foi desenvolvido com o propósito específico de consolidar conhecimentos avançados em **construção de layouts** e **arquitetura de CSS**.

Diferente de aplicações focadas puramente em lógica de dados, o "Projeto 3" resolve o desafio da **apresentação visual**: como entregar uma página leve, semanticamente correta e que proporcione uma experiência de leitura fluida tanto em celulares pequenos quanto em monitores ultrawide. Ele serve como base para a criação de sites institucionais e páginas de captura de leads.

## 🖼️ Demonstração Visual

*(Sugestão: Insira aqui um GIF navegando pela página ou um print da versão Desktop vs Mobile)*
## 🛠️ Tecnologias Utilizadas

A stack tecnológica foi escolhida priorizando a componentização e a facilidade de manutenção de estilos:

* **[React.js](https://reactjs.org/):** Biblioteca para componentização da interface, permitindo o reuso de cabeçalhos, rodapés e seções de conteúdo.
* **[CSS Modules / Styled Components](https://styled-components.com/):** (Ajuste conforme seu código) Utilizado para evitar conflitos de classes globais e manter o estilo escopado ao componente.
* **[Media Queries]:** Implementação manual de pontos de quebra (breakpoints) para garantir responsividade total.
* **[Vite/CRA]:** Ferramenta de build para otimização e minificação dos arquivos finais.

## 📦 Instalação e Configuração

Siga as instruções abaixo para configurar o ambiente de desenvolvimento localmente.

### Pré-requisitos
* [Node.js](https://nodejs.org/) (v16+)
* NPM ou Yarn instalado.

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/DouglassenG/_projeto_3.git](https://github.com/DouglassenG/_projeto_3.git)
    ```

2.  **Entre na pasta do projeto:**
    ```bash
    cd _projeto_3
    ```

3.  **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

4.  **Inicie o servidor local:**
    ```bash
    npm run dev
    # ou
    npm start
    ```
    O projeto abrirá automaticamente em `http://localhost:3000` (ou 5173 se usar Vite).

## 💻 Uso e Exemplos

O projeto é estruturado em seções verticais típicas de uma Landing Page:

1.  **Hero Section:** Apresentação principal com Call to Action (CTA).
2.  **Features/Sobre:** Grid de ícones e textos explicativos.
3.  **Galeria:** Exposição visual de imagens responsivas.
4.  **Rodapé:** Links de navegação e contato.

Exemplo de estrutura de componente utilizada:
```jsx
// Exemplo de como os componentes são chamados para montar a página
function App() {
  return (
    <>
      <Header />
      <HeroBanner title="Bem-vindo ao Projeto" />
      <FeaturesGrid />
      <Footer />
    </>
  );
}
