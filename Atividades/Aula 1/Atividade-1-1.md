# 🔍 Atividade 01 - Projeto em Vanilla JS (Escape Misterioso)

> **Disciplina:** Frameworks Front-end
> **Professor:** Prof. Me. Deivison S. Takatu — deivison.takatu@edu.senai.br
> **Tecnologia:** Vanilla JS (HTML, CSS e JavaScript puros)

![Atividade](https://img.shields.io/badge/atividade-01%20Vanilla%20JS-blue)
![Tema](https://img.shields.io/badge/tema-Projeto%20Prático%20em%20JavaScript%20Puro-green)
![Status](https://img.shields.io/badge/status-concluída-brightgreen)

## 📑 Índice

1. [Resumo da Atividade](#-resumo-da-atividade)
2. [Sobre o Projeto](#-sobre-o-projeto)
3. [Como Jogar](#-como-jogar)
4. [Mecânicas de Gamificação](#-mecânicas-de-gamificação)
5. [Estrutura do Projeto](#-estrutura-do-projeto)
6. [Tecnologias](#-tecnologias)
7. [Deploy](#-deploy-da-atividade)
8. [Checklist da Atividade](#-checklist-da-atividade)

---

## 📝 Resumo da Atividade

A Atividade 01 consistiu em criar um projeto utilizando **Vanilla JS** (HTML, CSS e JavaScript puros, sem frameworks ou bibliotecas), conectar o editor de código (IDE) ao GitHub e realizar o **deploy** da aplicação pela ferramenta **Vercel**. O projeto desenvolvido foi o jogo **"Escape Misterioso"**, um jogo *point-and-click* gamificado, que exercita os fundamentos de manipulação do DOM, estilização e lógica de interface abordados na Aula 1 - Vanilla JS.

## 🎮 Sobre o Projeto

Jogo **point-and-click** gamificado, feito inteiramente com **Vanilla JS** (HTML, CSS e JavaScript puros, sem frameworks ou bibliotecas).

O jogador explora uma sala misteriosa, interagindo com objetos visíveis e encontrando itens escondidos para conseguir abrir a porta e vencer.

## ▶️ Como Jogar

1. Abra o `index.html` no navegador (duplo clique).
2. Clique nos objetos visíveis da sala (planta, quadro, livro, relógio e lâmpada) para ganhar pontos e dicas.
3. Encontre os **3 itens escondidos** (🔑 Chave de Prata, 🗝️ Chave de Bronze e 💎 Cristal Mágico). Eles começam **invisíveis** — clique nas áreas certas para revelá-los e guardá-los na mochila.
4. Quando tiver os 3 itens, a porta 🚪 acende e pode ser aberta para vencer.
5. Use o botão **Dica** 💡 para revelar temporariamente a posição dos itens escondidos e **Reiniciar** ↺ para recomeçar.

## 🏆 Mecânicas de Gamificação

- **Pontuação ⭐** por cada interação.
- **XP e Níveis 🎖️**: a cada 100 XP você sobe de nível.
- **Inventário** de 4 slots (3 itens necessários + 1 extra).
- **Cronômetro ⏱️** com bônus de tempo na vitória.
- **Toasts** de feedback e tela de vitória com resumo final.

## 📁 Estrutura do Projeto

```
index.html   Estrutura e HUD (nível, XP, pontos, timer, mochila, overlay)
style.css    Visual da sala, hotspots, animações e layout responsivo
script.js    Lógica do jogo: cena, itens, inventário, XP, timer e fim de jogo
```

- **`index.html`** — marcação da página e HUD (cabeçalho com nível, XP, pontos, timer, mochila e overlay de vitória).
- **`style.css`** — estilização da sala, hotspots clicáveis, animações e layout responsivo.
- **`script.js`** — lógica do jogo: cena, itens, inventário, XP, cronômetro e condição de fim de jogo, usando manipulação do DOM puro.

## 🛠️ Tecnologias

- **HTML5** — estrutura da página e HUD.
- **CSS3** — animações e gradientes, sem imagens externas.
- **JavaScript (ES6)** — manipulação do DOM puro, sem frameworks ou bibliotecas.
- **Git e GitHub** — versionamento do código.
- **Vercel** — deploy/hospedagem da aplicação.

## 🚀 Deploy da Atividade

🔗 **Repositório:** https://github.com/Felipe-Pinheiro-Lopes/senai-projeto-vanilla
🌐 **Deploy (Vercel):** https://senai-projeto-vanilla-mu.vercel.app/

## ✅ Checklist da Atividade

- [x] Criar projeto em Vanilla JS (HTML, CSS e JavaScript puros)
- [x] Conectar o IDE ao GitHub e versionar o código
- [x] Implementar a lógica do jogo (Escape Misterioso)
- [x] Realizar o deploy na Vercel
- [x] Documentar a atividade neste arquivo Markdown
