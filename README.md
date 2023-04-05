# Pagina_login
BackLog
Fazer o botão do bloco .cobrir
Fazer o Navbar entrar e cadastrar de forma interativa
Fazer a Logo ter propriedade onclick
Mudar os nomes da funções

var contador = 0
    function animacao_cadastrar() {
        if (div_bloco.classList != "direita" ) {
            div_bloco.classList.remove("esquerda")
            div_bloco.classList.add("direita")
            contador++
            button_cobrir.innerHTML =`Entrar`
            button_cobrir.setAttribute("onclick", "animacao_entrar(this);")
        } 
    }
    function animacao_entrar() {
        if (contador != 0) {
        if (div_bloco.classList != "esquerda") {
        div_bloco.classList.remove("direita")
        div_bloco.classList.add("esquerda")
        button_cobrir.innerHTML =`Cadastrar`
        button_cobrir.setAttribute("onclick", "animacao_cadastrar(this);")
        }
    }
    }
