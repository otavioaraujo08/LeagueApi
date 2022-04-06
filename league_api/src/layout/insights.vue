<template>
    <body>
        <div class="circulos">
            <span class="circulo">
                <h1>+ 150</h1>
                <h2>Campeões</h2>
            </span>
        </div>
        <div class="circulos">
            <span class="circulo">
                <h1>+ 1.200</h1>
                <h2>Skins</h2>
            </span>
        </div>
        <div class="circulos">
            <span class="circulo">
                <h1>+ 815</h1>
                <h2>Habilidades</h2>
            </span>
        </div>
        <div class="circulos">
            <span class="circulo">
                <h1>+ 130</h1>
                <h2>Itens</h2>
            </span>
        </div>
    </body>
</template>

<script>
export default {
    name: 'Insights',
}
</script>

<style scoped>

body {
    text-align: center;
    display: flex;
}

h1 {
    color: #f0efeb;
    font-size: 50px;
    font-family: 'Oswald', sans-serif;
}

h2 {
    color: #DB4FD1;
    font-size: 25px;
    font-family: 'Encode Sans Semi Expanded', sans-serif;
}

h1, h2 { 
    margin-top: 40px;
    text-align: center;
}

.circulo { 
  height: 250px;
  width:  250px;
  background-color: transparent;
  display: block;
  border-radius: 50%;
  border-style: solid;
  border-color: #DB4FD1;
}

.circulos { 
    margin: 32px 32px;
}
</style>
