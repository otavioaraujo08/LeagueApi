<template>
  <div class="home">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    
    <Header/>
    <Body/>
    <Generico
      TextoBase="Venha se divertir com a gente"
      teemo="sim"
    />
    <Insight/>
    <Footer/>
  </div>
</template>

<script>
import Header   from '@/layout/header.vue'
import Body     from '@/layout/body.vue'
import Generico from '@/components/generico.vue'
import Insight  from '@/layout/insights.vue'
import Footer  from '@/layout/footer.vue'

export default {
  name: 'Home',

  components: {
    Header,
    Body,
    Generico,
    Insight,
    Footer
  }
}
</script>

<style>
</style>
