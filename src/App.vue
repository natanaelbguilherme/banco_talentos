<template>
  <Menu />

  <router-view></router-view>
  
  RODAPE
</template>


<script>
import Menu from './components/Menu/Menu.vue'

export default {
  components: {
    Menu
  }
}
</script>
