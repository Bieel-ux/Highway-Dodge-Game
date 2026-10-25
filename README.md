# Highway Dodge

<div align="center">

<img src="https://img.shields.io/badge/Status-Concluído-2ea44f?style=for-the-badge" alt="Status do projeto">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">

  
  


**Um jogo de reflexos, velocidade e sobrevivência na rodovia.**

Jogo 2D desenvolvido com HTML5, CSS3, JavaScript e Canvas API como projeto acadêmico de Programação Orientada a Objetos.

</div>

---

## 🎮 Sobre o projeto

O **Highway Dodge** é um jogo 2D no qual o jogador controla um carro em uma rodovia movimentada e precisa desviar dos veículos inimigos pelo maior tempo possível.

Durante a partida, o jogador deve controlar o carro, evitar colisões, acumular pontos e superar o próprio recorde. Conforme a pontuação aumenta, novos veículos podem ser desbloqueados na garagem e o nível de dificuldade também evolui.

O projeto foi desenvolvido com foco na aplicação prática de conceitos de **Programação Orientada a Objetos**, manipulação do Canvas, eventos de teclado, efeitos sonoros e desenvolvimento responsivo.

## 🚗 Funcionalidades

- 🎯 Movimentação do carro utilizando teclado ou setas direcionais.
- 🛣️ Rodovia animada com veículos em diferentes faixas.
- 🚙 Trânsito com veículos de diferentes tipos e sentidos.
- 🚘 Aparição de até três veículos simultaneamente.
- 💥 Sistema de colisão.
- 🏆 Sistema de pontuação e recorde.
- 📈 Dificuldade progressiva.
- ⚡ Bônus por ultrapassagens arriscadas.
- 🏁 Garagem com veículos desbloqueáveis.
- 🔄 Seleção de diferentes carros.
- ⏸️ Sistema de pausa e retomada da partida.
- 🔁 Opção para reiniciar o jogo.
- 🕹️ Tela de fim de jogo.
- 🔊 Efeitos sonoros durante a partida.
- 📱 Interface responsiva para diferentes tamanhos de tela.

## 🕹️ Como jogar

O objetivo principal é sobreviver o maior tempo possível na rodovia sem colidir com os veículos inimigos.

Durante a partida:

1. Controle o carro utilizando as teclas disponíveis.
2. Desvie dos veículos que aparecem na pista.
3. Tente realizar ultrapassagens arriscadas para conseguir bônus.
4. Acumule pontos e aumente seu recorde.
5. Utilize a garagem para selecionar e desbloquear novos carros.

## 🎮 Controles

| Tecla | Ação |
|:---:|---|
| `W` ou `↑` | Mover para cima |
| `S` ou `↓` | Mover para baixo |
| `A` ou `←` | Mover para a esquerda |
| `D` ou `→` | Mover para a direita |
| `P` ou `Esc` | Pausar ou continuar |

## 🛠️ Tecnologias utilizadas

- 🧱 **HTML5** — estrutura das telas e elementos do jogo.
- 🎨 **CSS3** — estilização, layout e responsividade.
- ⚙️ **JavaScript** — lógica da aplicação e interação com o usuário.
- 📦 **JavaScript ES Modules** — organização dos módulos do projeto.
- 🖼️ **Canvas API** — renderização da pista, veículos e elementos visuais.
- 🔊 **Audio API** — reprodução dos efeitos sonoros.
- 💾 **Local Storage** — armazenamento do recorde e dados da garagem.

## 🧠 Arquitetura do projeto

O projeto é dividido em classes e módulos para organizar melhor as responsabilidades do sistema:

| Arquivo | Responsabilidade |
|---|---|
| `js/Jogo.js` | Controla o estado principal da partida, pontuação, recorde e colisões. |
| `js/Carro.js` | Define a estrutura base dos veículos. |
| `js/CarroJogador.js` | Controla o carro utilizado pelo jogador. |
| `js/CarroInimigo.js` | Controla os veículos que aparecem na rodovia. |
| `js/Garagem.js` | Gerencia seleção, desbloqueio e armazenamento dos carros. |
| `js/Som.js` | Controla os efeitos sonoros do jogo. |
| `js/script.js` | Inicializa o jogo, controla os eventos e executa o loop principal. |
| `css/style.css` | Define os estilos da tela principal do jogo. |
| `css/inicio.css` | Define os estilos da tela inicial. |
| `css/garagem.css` | Define os estilos da garagem e dos veículos. |
| `index.html` | Estrutura principal da aplicação. |

## 🧩 Conceitos de Programação Orientada a Objetos

O projeto aplica diversos conceitos de POO:

- 🧱 **Classes e objetos:** utilizados para representar o jogo, os carros, a garagem e o sistema de som.
- 🌳 **Herança:** as classes `CarroJogador` e `CarroInimigo` utilizam a classe base `Carro`.
- 🔒 **Encapsulamento:** cada classe organiza seus próprios atributos e métodos.
- 🎯 **Abstração:** as responsabilidades do sistema são divididas em diferentes módulos.
- 🔄 **Polimorfismo:** os diferentes tipos de carros possuem comportamentos específicos.
- 📦 **Modularização:** o código é separado em arquivos com funções bem definidas.

## 🚀 Instalação

### 📋 Pré-requisitos

- Navegador moderno com suporte a JavaScript ES Modules.
- Python 3, caso queira utilizar um servidor local.
- Visual Studio Code com a extensão Live Server, como alternativa.

### 🪟 Executando no Windows

1. Clone ou baixe este repositório.
2. Acesse a pasta do jogo:

   ```text
   Jogo (Sintonia Tech)/highway-dodge
