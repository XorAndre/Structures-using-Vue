<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <About></About>
    
  </div>
</template>

<script>
// @ is an alias to /src
import About from '@/components/About.vue'

export default {
  name: 'home',
  components: {
    About
  }
}
</script>
