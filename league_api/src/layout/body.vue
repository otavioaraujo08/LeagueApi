<template>
    <div class="page-wrap">
    
        <div class="lado_esquerdo">
            <div class="illustration">
            </div>
        </div>

        <div class="lado_direito">
            <h1>
                Suba de elo com estatísticas !
            </h1>
            <p>Todo nosso sistema simplifca os dados para que você tenha as melhores dicas na hora de se divertir.</p>
            <img  class="icone" src="../assets/rammus.png">
        </div>
  </div>
</template>

<script>
export default {
    name: 'Body',
    
}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

h1 {
  font-family: 'Oswald', sans-serif;
}

p {
  color: #A9B2BD;
  font-family: 'Shippori Mincho B1', serif;
  font-size: 20px;
  max-width: 400px;
  margin-bottom: 40px;
}

.page-wrap {
  display: flex;
  min-height: 74vh;
}

.lado_esquerdo {
  background-image: url(../assets/yorick.jpg);
  background-repeat: no-repeat;
  flex: 1 1 66.666%;
  display: flex;
}

.lado_direito {
  background: #001524;
  flex: 1 1 33.333%;
  padding: 25px;
}

.lado_direito h1 {
  margin-top: 60px;
  font-size: 35px;
  font-weight: 400;
  margin-bottom: 25px;
  text-align: center;
}

.lado_direito h1 {
  color: #68758D;
  font-weight: 900;
}

.icone {
  width: 200px;
  height: auto;
  display: block;
  margin: auto;
}
</style>