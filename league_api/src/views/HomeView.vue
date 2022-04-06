<template>
  <div class="home">
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
