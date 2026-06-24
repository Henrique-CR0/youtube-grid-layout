# 📺 Desafio Grid — Listagem de Vídeos do YouTube

Projeto desenvolvido como parte do desafio de **CSS Grid Layout** da [Digital Innovation One (DIO)](https://www.dio.me/). O objetivo é construir uma página de listagem de vídeos no estilo do YouTube, aplicando na prática os conceitos de **CSS Grid**.

## 🎯 Sobre o projeto

A página recria a interface de listagem de vídeos do YouTube (tema escuro), com header fixo, barra lateral de navegação e um grid de vídeos totalmente responsivo. Todo o layout estrutural foi construído com **CSS Grid**, demonstrando o controle de linhas e colunas de forma bidimensional.

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica da página
- **CSS3** — estilização e layout
- **CSS Grid Layout** — organização estrutural da página e do grid de vídeos
- **Font Awesome** — ícones da interface

## ✨ Conceitos de Grid aplicados

- `grid-template-areas` para montar o layout geral (header, sidebar e conteúdo)
- `grid-template-columns` e `grid-template-rows` para definir a estrutura
- `repeat()`, `minmax()` e `auto-fill` para um grid de vídeos responsivo, que ajusta o número de colunas automaticamente conforme a largura da tela
- Reorganização do layout em diferentes breakpoints com **media queries**

## 📱 Responsividade

O layout se adapta a diferentes tamanhos de tela:

- **Desktop:** sidebar completa + grid com várias colunas
- **Tablet:** sidebar compacta (apenas ícones)
- **Mobile:** sidebar oculta e vídeos em coluna única

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/desafio-grid-dio.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd desafio-grid-dio
   ```
3. Abra o arquivo `index.html` no navegador (ou use a extensão **Live Server** no VS Code).

## 📂 Estrutura de arquivos

```
desafio-grid-dio/
├── index.html
└── assets/
    └── css/
        └── style.css
```

## 📝 Observações

As imagens e ícones utilizados são carregados via links externos (placeholders), servindo apenas para fins de demonstração do layout.

---

Projeto desenvolvido com fins educacionais durante a trilha de CSS da DIO. 💙