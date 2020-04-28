<template>
  <div class="home">
    <main>
      <HomePage/>
    </main>
  </div>
</template>

<script>
// @ is an alias to /src
import HomePage from '@/home/HomePage.vue'

export default {
  name: 'Home',
  components: {
    HomePage
  }
}
</script>
