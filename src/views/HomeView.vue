<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

    <h1>鹅鹅鹅</h1>
    <h1>曲项向天歌</h1>
    <h1>白毛浮绿水</h1>
    <h1>红掌拨清波</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  data() {
    return {
      info:'泰酷辣',
    }
  },
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
