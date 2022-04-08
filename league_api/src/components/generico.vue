<template>
    <div class="titulo">
        <h1> {{ TextoBase }} </h1>
        <img v-if="teemo == 'sim'" src="../assets/teemo.png">
    </div>
</template>

<script>
export default {
    name: "generico.vue",
    
    props: {
        TextoBase: String,
        teemo: String,
    }
}
</script>

<style>
    .titulo {
        margin-top: 30px;
        text-align: center;
        font-size: 19px;
        font-family: 'Oswald', sans-serif;
        color: #f1faee;
        text-shadow: 2px 2px red;
    }

    img {
        width: 20%;
    }
</style>