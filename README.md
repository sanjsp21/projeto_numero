programa para gerar numero

<body>

    <div class="container">
        <div class="container__conteudo">
            <div class="container__informacoes">
                <div class="container__texto">
                    <h1>Adivinhe o <span class="container__texto-azul">numero secreto</span></h1>
                    <p class="texto__paragrafo">Escolha um número entre 1 a 80</p>
                </div>
                <input type="number" min="1" max="10" class="container__input">
                <div class="chute container__botoes">
                    <button onclick="verificarChute()" class="container__botao">Chutar</button>
                    <button onclick="reiniciarJogo()" id="reiniciar" class="container__botao" disabled>Novo jogo</button>
                </div>
            </div>
            <img src="./img/ia.png" alt="Uma pessoa olhando para a esquerda" class="container__imagem-pessoa" />
        </div>
    </div>




    <script src="app.js" defer></script>
</body>

</html>