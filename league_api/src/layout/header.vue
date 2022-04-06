<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

    <header>
        <img 
            src="../assets/logo.png"
            style="width: 60px; height: 60px"
        > 

        <ul>
            <li>Campeões</li>
            <li>Itens</li>
            <li>Estatísticas</li>
            <li>Sobre o Game</li>
        </ul>

        <div class="icones">
            <span class="material-icons">search</span>
            <span class="material-icons">code</span>
        </div>
    </header>
</template>

<script>
export default {
    name: 'header',
    
}
</script>

<style>
    header {
        align-items: center;
        display: flex;
        justify-content: space-around;
        background: rgba(255, 255, 255, 0.24);
        box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        backdrop-filter: blur(5px);
        -webkit-backdrop-filter: blur(5px);
        border: 1px solid rgba(255, 255, 255, 0.3);
    }

    ul {
        display: flex;
        list-style-type: none;
        flex-direction: row;
    }

    li {
        margin-right: 25px;
        font-size: 21px;
        font-family: 'Oswald', sans-serif;
        color: #dee2e6;
    }

    li:hover {
        color: #fca311;
        transition-delay: 0.1s;
        cursor: pointer;
    }

    .material-icons {
        margin-right: 30px;
    }
</style>
