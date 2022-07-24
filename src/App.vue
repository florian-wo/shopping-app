<template>
  <main class="w-screen h-screen flex justify-center items-center">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </main>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>