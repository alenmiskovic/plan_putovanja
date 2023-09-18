<template>
  <div class="home-view">
    <div class="container">
      <h1>Isplanirajte svoje putovanje</h1>
      <p>Ovo je vaše mjesto za planiranje i praćenje putovanja.</p>

      <!-- Dodajte ostale komponente i sadržaj ovdje -->

      <router-link to="/destinacije" class="btn btn-primary">Pregledaj destinacije</router-link>
    </div>
  </div>
</template>


<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
