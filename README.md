# SyntaxWear E-commerce

SyntaxWear é um projeto de site de e-commerce para uma loja de tênis fictícia. O layout é moderno, responsivo e focado na apresentação dos produtos.

## Visão Geral

Este projeto é uma implementação front-end de uma página inicial para um site de e-commerce. Ele inclui um cabeçalho de navegação fixo, uma seção de herói, categorias de produtos, um grid de produtos em destaque e um rodapé com formulário de newsletter e links de navegação.

## Tecnologias Utilizadas

*   **HTML5:** Para a estrutura semântica do site.
*   **CSS3:** Para estilização, layout e responsividade. O CSS é organizado de forma modular, utilizando variáveis para facilitar a manutenção.

## Estrutura de Arquivos

O projeto está organizado da seguinte forma:

```
ecommerce-syntaxwear/
├── css/
│   ├── base.css           # Estilos base (corpo, tipografia)
│   ├── reset.css          # Reset de estilos do navegador
│   ├── variables.css      # Variáveis CSS (cores, fontes)
│   └── components/
│       ├── footer.css     # Estilos do rodapé
│       ├── header.css     # Estilos do cabeçalho
│       ├── hero.css       # Estilos da seção de herói
│       ├── product-category.css # Estilos das categorias de produto
│       └── product-grid.css   # Estilos do grid de produtos
├── images/
│   ├── banners/
│   │   └── hero.jpg
│   ├── icons/
│   │   └── (ícones SVG para redes sociais, etc.)
│   ├── logo/
│   │   └── logo.svg
│   └── products/
│       └── (imagens dos produtos)
├── index.html             # Arquivo principal da página
└── README.md              # Este arquivo
```

## Como Executar

Este é um projeto de front-end estático. Para visualizá-lo, basta abrir o arquivo `index.html` em qualquer navegador web.

1.  Clone este repositório:
    ```sh
    git clone https://github.com/maski-yofem/ecommerce-syntaxwear.git
    ```
2.  Navegue até o diretório do projeto:
    ```sh
    cd ecommerce-syntaxwear
    ```
3.  Abra o arquivo `index.html` no seu navegador de preferência.

## Funcionalidades

*   **Layout Responsivo:** O site se adapta a diferentes tamanhos de tela, de dispositivos móveis a desktops.
*   **Navegação Fixa:** O cabeçalho permanece visível no topo da página durante a rolagem.
*   **Menu Hambúrguer:** Em telas menores, a navegação principal é substituída por um menu hambúrguer.
*   **Estilização Modular:** O CSS é dividido em componentes, facilitando a manutenção e a escalabilidade do código.
