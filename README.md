# Mercado Preso

E-commerce fictício desenvolvido com **HTML5** e **CSS3** puro (sem frameworks ou bibliotecas externas). O projeto simula uma loja online completa, com página inicial de produtos e página de detalhes de produto individual.

## 📋 Sobre o projeto

O **Mercado Preso** conta atualmente com duas páginas principais:

### 🏠 Home (`index.html`)
- Header fixo com logo, título e barra de pesquisa centralizada
- Banner de destaque/ofertas
- Grade de produtos com imagem, nome e preço, cada card linkando para sua respectiva página de detalhes
- Footer com formulário de contato, links de ajuda/políticas e seção "Sobre nós"

### 📦 Página de Produto (`produto1.html`)
- Botão de voltar para a home
- Galeria com imagem do produto
- Título, avaliação (com âncora para seção de opiniões), preço e descrição detalhada
- Seletor de quantidade, com informação de estoque disponível
- Botões de ação: "Comprar agora" e "Adicionar ao carrinho"
- Selo de frete grátis com prazo estimado de entrega
- Seção de avaliações de clientes

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica da página
- **CSS3** — estilização customizada, com uso extensivo de Flexbox

## 📁 Estrutura de arquivos

```
├── index.html      # Página inicial (home) com lista de produtos
├── produto1.html   # Página de detalhes do produto
├── style.css       # Estilos do site
└── README.md       # Este arquivo
```

## 🎨 Funcionalidades / destaques do layout

- **Header** com barra de pesquisa centralizada via `position: absolute` + `transform: translateX(-50%)`
- **Banner de ofertas** ocupando a largura total da página
- **Lista de produtos** organizada em cards com `display: flex`, com o card do Produto 1 já navegando para sua página de detalhes (demais produtos ainda sem página própria)
- **Layout de produto** estruturado com Flexbox (`display: flex` em `column` e `row`), separando imagem, informações e área de compra
- **Seletor de quantidade** customizado, exibindo estoque disponível
- **Footer** dividido em 3 colunas (contato, ajuda/políticas, sobre nós), alinhadas com `margin: auto`
- Formulário de contato com campos de nome, e-mail e mensagem

## 🚀 Como rodar o projeto

Não é necessário nenhuma instalação. Basta:

1. Baixar ou clonar todos os arquivos (`index.html`, `produto1.html` e `style.css`, mantendo-os na mesma pasta)
2. Abrir o arquivo `index.html` diretamente no navegador

## 📄 Licença

Projeto de estudo/portfólio — livre para uso e modificação.
