# Piedra_papel_tijera
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
        <title> Piedra, papel o tijera </title>
        <script> 
            
            // 1 es piedra, 2 es papel y 3 es tijera 
            let jugador = 0
            let pc = Math.floor(Math.random() * (3 - 1 + 1) + 1)
            jugador = prompt("Elige: 1 para 🥌, 2 para 📄, 3 para ✂️")
            // alert("Elegiste " + jugador)
            if (jugador == 1) { 
                alert("Elegiste 🥌")
            } else if(jugador == 2) {
                alert("Elegiste 📄")
            } else if(jugador == 3){
                alert("Elegiste ✂️")
            } else {
                alert("PERDEDOR")
            }  

            if (pc == 1) {
                alert("Pc Eligió 🥌")
            } else if(pc == 2) {
                alert("Pc Eligió 📄")
            } else if(pc == 3){
                alert("PC Eligió ✂️")
            }  
            //COMBATE

            if (pc == jugador) {
                alert("ES UN EMPATE")
            }else if (jugador == 1 && pc == 3) {
                alert("ERES EL GANADOR")
            }else if (jugador == 2 && Pc == 1) {
                alert("ERES EL GANADOR")
            }else if (jugador == 3 && Pc == 2) {
                alert("ERES EL GANADOR")
            }else{
                alert("PC GANA")
            }
        </script>
    </head>
    <body>
        <h1>Piedra, papel o tijera</h1>
    </body>

</html>
