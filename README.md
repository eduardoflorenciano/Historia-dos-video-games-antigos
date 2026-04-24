# História dos Videogames Antigos

Site informativo e apaixonado sobre a história dos consoles clássicos — do Atari Pong ao PlayStation 2 — com imagens, curiosidades, jogabilidade e listas dos jogos mais vendidos de cada plataforma.

---

## Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Conteúdo Abordado](#-conteúdo-abordado)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Conceitos de HTML Aplicados](#-conceitos-de-html-aplicados)
- [Como Visualizar](#-como-visualizar)

---

## Sobre o Projeto

Este é um site informativo criado por um colecionador e entusiasta de videogames antigos. A página reúne textos históricos, imagens e listas sobre alguns dos consoles mais icônicos da história dos jogos eletrônicos, desde o pioneiro Atari Pong (1972) até o PS2 — o console mais vendido de todos os tempos.

O projeto foi desenvolvido utilizando apenas **HTML5 puro**, sem frameworks ou folhas de estilo externas, com foco em estrutura semântica e marcação correta do conteúdo.

---

## Conteúdo Abordado

### Atari Pong (1972)
- História e impacto cultural do primeiro jogo comercialmente bem-sucedido
- Descrição completa da jogabilidade (paletas, ângulos, velocidade da bola)
- Imagens do console e da tela do jogo
- Links para fontes externas (Wikipédia)

### Brick Game & Tetris
- Origem do console portátil Brick Game e sua popularidade no Brasil nos anos 90
- História do Apollo, primeiro aparelho com Tetris no Brasil
- Descrição da jogabilidade do Tetris (tetraminós, linhas, pontuação)
- Imagens do dispositivo e do jogo

### Super Nintendo (SNES)
- Lançamento do console de 16 bits da Nintendo (1990–1993 globalmente)
- Comparativo com o NES e os chips de aprimoramento integrados
- Galeria com 3 imagens: console, cartuchos e Super Mario World
- **Top 10 jogos mais vendidos** com números de unidades (ex.: Super Mario World — 20,61 mi)

### PlayStation 1 (1994)
- Primeiro console da Sony e a transição dos cartuchos para CDs
- Marco histórico: mais de 100 milhões de unidades vendidas
- A parceria original com a Nintendo que deu origem ao PS1
- **Top 10 jogos mais vendidos** (ex.: Gran Turismo — 10,85 mi, Final Fantasy VII — 9,72 mi)

### PlayStation 2 (2000)
- O console mais vendido de todos os tempos (155+ milhões de unidades)
- Contexto do lançamento e o fenômeno de escassez nas lojas
- Mais de 4.000 jogos licenciados e último título lançado em 2013
- **Top 10 jogos mais vendidos** (ex.: GTA San Andreas — 17,33 mi)

---

## Estrutura do Projeto

```
Historia-dos-video-games-antigos/
│
├── index.html              # Página única com todo o conteúdo do site
│
└── Imagens/
    ├── atari-pong.jpg             # Console Atari Pong
    ├── pong.webp                  # Tela do jogo Pong
    ├── brick-games.webp           # Console Brick Game
    ├── tetris.webp                # Jogo Tetris
    ├── super-nintendo.jpg         # Console Super Nintendo
    ├── cartuchos.webp             # Cartuchos do SNES
    ├── jogo-mario.webp            # Super Mario World
    ├── video-game-console-22.jpg  # PlayStation 1
    ├── pessoa_jogando1.jpg        # Pessoa jogando PS1
    ├── playstation2.jpg           # PlayStation 2
    ├── game.webp                  # Imagem geral de game
    └── cube.webp                  # Imagem complementar
```

---

## Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Toda a estrutura, conteúdo e semântica da página |

Nenhuma dependência externa, framework ou biblioteca é utilizada. O projeto roda diretamente no navegador sem configuração adicional.

---

## Conceitos de HTML Aplicados

O projeto serve também como exercício prático de HTML semântico. As tags utilizadas e seus propósitos estão documentados nos comentários do próprio código:

| Tag | Uso no Projeto |
|---|---|
| `<!DOCTYPE html>` | Declaração do HTML5 |
| `<head>` / `<title>` | Configuração da aba do navegador |
| `<meta charset>` | Suporte a caracteres especiais e acentuação |
| `<h1>` | Título principal da página |
| `<h2>` | Nome de cada console (subtítulos de seção) |
| `<h3>` | Jogabilidade e listas de jogos mais vendidos |
| `<p>` | Parágrafos de texto histórico |
| `<figure>` / `<figcaption>` | Imagens com crédito de fonte |
| `<img>` com `alt` e `title` | Imagens acessíveis com descrição alternativa |
| `<a href>` | Links externos para fontes de pesquisa |
| `<ul>` / `<li>` | Listas dos jogos mais vendidos |
| `<hr>` | Separadores visuais entre seções |

---

## Como Visualizar

Por ser um projeto de arquivo único em HTML puro, não requer instalação ou servidor.

**Opção 1 — Abrir diretamente no navegador:**

1. Clone ou baixe o repositório:
   ```bash
   git clone https://github.com/seu-usuario/Historia-dos-video-games-antigos.git
   ```
2. Abra o arquivo `index.html` no seu navegador.

**Opção 2 — Live Server (para desenvolvimento):**

1. Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code.
2. Clique com o botão direito em `index.html` → **"Open with Live Server"**.

> **Atenção:** Mantenha a pasta `Imagens/` no mesmo diretório que o `index.html` para que todas as imagens carreguem corretamente.
