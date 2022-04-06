<template>
    <div class="page-wrap">
    
        <div class="left-panel">
            <div class="illustration">
            </div>
        </div>

        <div class="right-panel">
            <h1>
                <strong>Welcome,</strong>
                Huuman
            </h1>
        </div>
  </div>
</template>

<script>
export default {
    name: 'Body',
    
    setup() {
        
    },
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: montserrat, sans-serif;
}

.page-wrap {
  display: flex;
  min-height: 74vh;
}

.left-panel {
  background-image: url(../assets/yorick.jpg);
  background-repeat: no-repeat;
  flex: 1 1 66.666%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.left-panel .illustration {
  margin-bottom: 50px;
}

.left-panel h2 {
  color: #FFF;
  font-size: 48px;
  font-weight: 400;
  text-align: center;
}

.right-panel {
  flex: 1 1 33.333%;
  padding: 25px;
}

.right-panel h1 {
  color: #FF5858;
  font-size: 48px;
  font-weight: 400;
  margin-bottom: 50px;
}

.right-panel h1 strong {
  color: #b7cc2e;
  font-weight: 900;
}
</style>