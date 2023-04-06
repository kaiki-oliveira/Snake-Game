# <div align="center"> 🐍Snake-Game</div>

<h1> 📖Sobre </h1>
<p>O famoso Jogo da Cobrinha (ou Snake Game) com JavaScript.O jogo foi desenvolvido atravez de pesquisas no google, youtube e repositorios no github de outros desenvolvedores.</p>

<hr>

<h1> 💻Demonstração</h1>

<div align="center">  <img src="https://user-images.githubusercontent.com/103068974/229660403-8239478d-7e9b-413d-b15d-0d0a02d2655a.png" width="400px" > </div>

<div align="center"> <a href="https://kaiki-oliveira.github.io/Snake-Game/" target="_blank">Clique aqui para jogar</a> </div>

<hr>
<h1>🛠Tecnologias e ferramentas utilizadas </h1>
<ul>
  <li> HTML5</li>
  <li> CSS3</li>
  <li> JavaScript</li>
</ul>

<hr>

<h1> 🔎Explicação </h1>

<p> O código começa declarando variáveis para as coordenadas x e y do jogador, bem como a velocidade. </p>

<p> A próxima linha declara uma variável para a trilha que será desenhada em cima de tudo. </p>
 
 <p>Em seguida, ele configura algumas funções para desenhar coisas na tela: ctx.fillStyle é definido como "#1a1c1b", que é preto com texto branco; ctx.fillRect desenha um retângulo em (x,y) com valores de largura e altura dados em pixels; game() inicia um loop infinito que atualiza cada quadro usando px += vx e py += vy . </p>
 
<p> A primeira instrução if verifica se a coordenada x do jogador foi ou não abaixo de 0, o que significa que ele está fora da tela para a esquerda ou para a direita. 
 Nesse caso, ele subtrai 1 de sua coordenada x para que eles possam voltar para a tela sem ter que redefinir sua posição toda vez que saem da tela.</p>
 
 <p> A segunda instrução if verifica se a coordenada y do jogador foi ou não abaixo de 0, o que significa que ele está fora da tela acima ou abaixo do nível do palco (o solo).
 Em caso afirmativo, ele subtrai 1 de sua coordenada y para que eles possam voltar ao palco novamente sem ter que redefinir sua posição toda vez que saem. </p>





