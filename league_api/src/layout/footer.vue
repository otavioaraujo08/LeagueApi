<template>
    <footer>
        <div class="container">
            <div>
                <h1 style="margin-top: 70px">
                    Desenvolvido de Fã Para Fã
                </h1>
                <p style="margin-top: 60px">™ & © 2022 Riot Games, Inc. Todos os direitos reservados. Riot Games, League of Legends e PvP.net são marcas
                ES EA aet EA TE iNEN
                </p>
            </div>
            <div>
                <img src="../assets/lee.png">
            </div>
        </div>
        <div class="container">
            <div>
                <img src="../assets/gnar.png">
            </div>
            <div>
                <h1 style="margin-top: 30px" > Desenvolvedores </h1>
                <li>
                    <a href="#!"><img class="redes-sociais" src="../assets/github.png">Marcos Aguiar</a>
                </li>
                <li>
                    <a href="#!"><img class="redes-sociais" src="../assets/github.png"> Otávio Araujo</a>
                </li>
                <li>
                    <a href="#!"><img class="redes-sociais" src="../assets/linkedin.png">Marcos Aguiar</a>
                </li>
                <li>
                    <a href="#!"><img class="redes-sociais" src="../assets/linkedin.png">Otávio Arajo</a>
                </li>
            </div>
        </div>

    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
a, li {
    list-style-type: none;
    color: #fca311;

}

li {
    margin-top: 20px;
}

a {
    margin-left: 250px;
    align-items: center;
    display: flex;
}

h1 {
    font-family: 'Anek Devanagari', sans-serif;
    color: #F9F9F9;
}

p {
    font-family: 'Quicksand', sans-serif;
    color: #98c1d9;
}

img {
    width: 300px
}

.container {  
  border: 5px;
  border-color: #fca311;
  border-style: solid;
  display: grid;
  grid-template-columns: 1.3fr 1.3fr;
  grid-template-rows: 1fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas: ". . .";
  text-align: center;
  background: #312244;
  height: auto;
}

.lista {
    display: flex;
    flex-direction: row;
}

.redes-sociais {
    margin-right: 20px;
    width: 40px;
}

</style>