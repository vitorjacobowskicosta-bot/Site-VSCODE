const botoes = document.querySelectorAll("button");

botoes.forEach(function (botao) {
    let curtiu = false; // Variável para controlar se o botão já foi clicado

    botao.addEventListener("click", botaoClicado);

    function botaoClicado() {
        let texto = botao.querySelector("span");

        if (curtiu === false) {
            texto.textContent++; // Incrementa o contador
            curtiu = true; // Marca como curtido
        } else {
            texto.textContent--; // Decrementa o contador
            curtiu = false; // Marca como não curtido
        }
    }
});
