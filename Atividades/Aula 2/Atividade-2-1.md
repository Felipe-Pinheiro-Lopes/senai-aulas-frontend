# 🐸 Atividade 02 - Projeto em React (Sapo na Estrada)

> **Disciplina:** Frameworks Front-end
> **Professor:** Prof. Me. Deivison S. Takatu — deivison.takatu@edu.senai.br
> **Framework escolhido:** React

![Atividade](https://img.shields.io/badge/atividade-02%20React-blue)
![Tema](https://img.shields.io/badge/tema-Projeto%20Prático%20em%20React-green)
![Status](https://img.shields.io/badge/status-concluída-brightgreen)

## 📑 Índice

1. [Resumo da Atividade](#-resumo-da-atividade)
2. [Sobre o Projeto](#-sobre-o-projeto)
3. [Tecnologias Utilizadas](#-tecnologias-utilizadas)
4. [Como Executar](#-como-executar)
5. [Deploy](#-deploy)
6. [Estrutura do Código](#-estrutura-do-código)
7. [Checklist da Atividade](#-checklist-da-atividade)

---

## 📝 Resumo da Atividade

A Atividade 02 consistiu em, em grupo, desenvolver um projeto prático utilizando o framework **React**, escolhido pelo grupo, e publicá-lo na web via **Vercel**, documentando o processo em um arquivo Markdown. O projeto desenvolvido foi o jogo **"Sapo na Estrada"** (estilo *Frogger*), no qual o jogador usa as setas do teclado para fazer o sapo atravessar as faixas de trânsito sem ser atropelado.

Esta atividade exercita os conceitos de componentização, estado (`useState`), efeitos (`useEffect`) e renderização com a **Canvas API**, abordados na Aula 2 - Configuração do Ambiente de Desenvolvimento.

## 🎮 Sobre o Projeto

Projeto React com um jogo do sapinho atravessando a rua (estilo Frogger). Use as setas do teclado para atravessar as faixas de trânsito sem ser atropelado.

- O sapo inicia na parte inferior e deve alcançar a parte superior (área segura).
- Cada faixa cruzada com sucesso soma pontos; ao ser atingido por um carro, o jogo termina e exibe o recorde.
- Pressione qualquer seta após o fim de jogo para reiniciar.

## 🛠️ Tecnologias Utilizadas

- **React** (biblioteca para construção de interfaces).
- **JavaScript (JSX)** com *hooks* `useState` e `useEffect`.
- **Canvas API** para renderização do jogo.
- **Create React App** como ferramenta de *scaffold*.
- **Vercel** para deploy/hospedagem.
- **Git e GitHub** para versionamento.

## ▶️ Como Executar

No diretório do projeto, você pode rodar:

### `npm start`

Executa o app em modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo no navegador.

A página recarrega quando você faz alterações.\
Você também pode ver erros de lint no console.

### `npm test`

Executa o *test runner* em modo interativo de observação.\
Veja a seção sobre [executar testes](https://facebook.github.io/create-react-app/docs/running-tests) para mais informações.

### `npm run build`

Compila o app para produção na pasta `build`.\
Ele empacota o React corretamente em modo de produção e otimiza o build para a melhor performance.

O build é minificado e os nomes de arquivos incluem os hashes.\
Seu app está pronto para ser deployado!

Veja a seção sobre [deployment](https://facebook.github.io/create-react-app/docs/deployment) para mais informações.

### `npm run eject`

> **Nota:** esta é uma operação sem volta. Uma vez que você usa `eject`, não pode voltar atrás!

Se você não estiver satisfeito com as escolhas de ferramenta e configuração, pode usar `eject` a qualquer momento. Esse comando removerá a dependência de build única do seu projeto.

Em vez disso, ele copiará todos os arquivos de configuração e as dependências transitivas (webpack, Babel, ESLint, etc.) para o seu projeto, dando a você controle total sobre eles. Todos os comandos, exceto `eject`, ainda funcionarão, mas apontarão para os scripts copiados para que você possa ajustá-los.

Você não precisa usar `eject`. O conjunto de funcionalidades disponível é adequado para implantações pequenas e médias, e você não deve se sentir obrigado a usá-lo.

## 🚀 Deploy & Repositório

🔗 [https://projeto-react-felipe-pl.vercel.app/](https://projeto-react-felipe-pl.vercel.app/)
🔗 [https://github.com/Felipe-Pinheiro-Lopes/projeto-react.git](https://github.com/Felipe-Pinheiro-Lopes/projeto-react.git)

## 🧩 Estrutura do Código

Principais pontos do `src/App.js`:

- **Grid do jogo:** `COLS = 13`, `ROWS = 11`, `TILE = 40` definem o tabuleiro.
- **Controles:** objeto `DIRS` mapeia as setas (`ArrowUp`, `ArrowDown`, `ArrowLeft`, `ArrowRight`) para deslocamentos.
- **Estado:** `useState` para `score`, `best` (recorde) e `message`; `useRef` (`stateRef`) para o estado mutável do loop de animação.
- **Loop de animação:** `requestAnimationFrame` desenha o cenário, move os carros das `lanes` e verifica colisões.
- **Lógica de pontuação:** ao alcançar a linha superior (`y === 0`) o sapo ganha +10 pontos e reinicia na base.
- **Colisão:** se o sapo ocupa a mesma linha de uma `lane` e sobrepõe um carro, `gameOver = true`.

## 📚 Saiba Mais

Você pode aprender mais na [documentação do Create React App](https://facebook.github.io/create-react-app/docs/getting-started) e para aprender React, consulte a [documentação do React](https://reactjs.org/).

## ✅ Checklist da Atividade

- [x] Escolher o framework (React) em grupo
- [x] Criar o projeto React e versionar no GitHub
- [x] Implementar a lógica do jogo (Sapo na Estrada)
- [x] Realizar o deploy na Vercel
- [x] Documentar a atividade neste arquivo Markdown
