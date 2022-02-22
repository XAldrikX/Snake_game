# Snake game

<div class="center">
    <img src="https://user-images.githubusercontent.com/88796366/155187016-cda2711b-cf30-4989-8cc0-fdb75a10a95f.png" width=800px>
</div


Esse projeto foi muito divertido fazer, a razão de ter escolhido estudar Frontend foi justamente poder criar algo dinâmico e acessível, onde posso colocar minha criatividade a prova e mostrar para as pessoas o que eu criei e elas poderem interagir com o jogo ou a web page, nesse desafio pude aprender métodos novos e rever outros que já sabia, como:<br>

<ul>
    <li>createElement. (Que uso para criar 100 divs que servirão como os quadrados que a cobra irá se movimentar)</li><br>
    <li>appendChild. (Usei para colocar as divs que criei com createElement dentro da div "grid")</li><br>
    <li>forEach. (Usado para dar uma classe aos quadrados usados para representar a cobra, e posteriormente retirar essa classe para que um novo jogo possa recomeçar)</li><br>
    <li>Math.floor / Math.random. (Utilizado para gerar aleatoriamente as maçãs que a cobra irá comer)</li><br>
    <li>setInterval> (Usado para invocar uma função chamada "move()" a cada um segundo, a cada maçã que a cobra come esse valor diminui fazendo assim que a cobra se movimente mais rápido)</li><br>
    <li>push / pop. (Utilizei esses métodos para dar a impressão de movimentação da cobra, como eu tinha 100 quadrados para trabalhar os quais tinham a classe de "square", eu tive que criar um array que iria conter os quadrados com a classe "snake", onde "tail" seria o ultimo índex do array e "currentSnake[0] o primeiro, desse jeito utilizando push e pop eu ia tirando a classe "snake" do último elemento desse array e push ia adicionando essa classe ao próximo índex, fazendo assim com que a cobra se movimente)</li><br>
    <li>A movimentação da cobra se faz de maneira simples, tendo um array que contem as 100 divs criadas anteriormente, para fazer a movimentação para a direita apenas adiciono 1 ao index, para a esquerda -1, para baixo adiciono 10 e para cima -10.</li><br>
    <li>Modulus operator %. (Modulus foi utilizado para a parte da lógica que identifica as bordas da div "grid")</li><br>
</ul>
<br>
A movimentação da cobra pode ser feita com as setas do teclado e também com botoes que adicionei posteriormente para usuários mobile conseguirem jogar.
<br>
<br>
Link do deployment --> https://xaldrikx.github.io/Snake_game/
