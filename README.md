# TechNews Today 🚀
> **Desenvolvimento Web • HTML5 + CSS3**
> 
> *Anatomia de um portal de notícias: cada tag explicada, do código à tela.*

---

## 📌 Sobre o Projeto

O **TechNews Today** é um portal de notícias moderno e responsivo desenvolvido como um desafio prático de desenvolvimento web. O objetivo principal do projeto é demonstrar a aplicação de tags semânticas do HTML5 combinadas com técnicas avançadas e modernas de estilização com CSS3.

---

## 🏗️ Anatomia das Tags HTML5 Utilizadas

O projeto foi estruturado com foco em semântica e acessibilidade. Abaixo estão as principais tags utilizadas:

| Tag | Descrição e Aplicação no Projeto |
|---|---|
| `<header>` | Cabeçalho principal do portal, contendo o logótipo e a tagline com efeito *glassmorphism*. |
| `<article>` | Representa o artigo em destaque sobre Inteligência Artificial, funcionando de forma independente. |
| `<details>` | Utilizado para criar a secção interativa "Leia mais" sem a necessidade de JavaScript. |
| `<iframe>` | Incorpora o reprodutor de vídeo externo na secção "Tech em Vídeo". |
| `<form>` | Formulário de subscrição de newsletter com campos de entrada, seleção e validação. |
| `<footer>` | Rodapé com os direitos de autor e informações de contacto semânticas (`<address>`). |

---

## 🎨 Destaques de Estilização (CSS3)

- **Layout Responsivo com CSS Grid:** Organização adaptável em colunas para ecrãs móveis e desktop.
- **Glassmorphism:** Efeito moderno de transparência com desfoque no cabeçalho (`backdrop-filter: blur()`).
- **Gradientes de Cores:** Combinações vibrantes e modernas para títulos, botões e cartões.
- **Micro-interações:** Efeitos sutis ao passar o cursor (`:hover`, `transition` e `transform`).

---

## 📁 Estrutura de Ficheiros

```text
.
├── index.html        # Estrutura e conteúdo semântico
└── Projeto10a.css    # Estilos e responsividade
