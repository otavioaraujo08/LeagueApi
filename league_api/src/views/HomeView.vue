<template>
  <div class="home">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    
    <Header/>
    <Body/>
  </div>
</template>

<script>
import Header from '@/layout/header.vue'
import Body from '@/layout/body.vue'

export default {
  name: 'Home',

  components: {
    Header,
    Body
  }
}
</script>

<style>
</style>
