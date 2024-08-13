<template>
  <div class="wrapper">
    <HeaderComp />
    <NavComp />
    <main class="container-fluid">
      <router-view />
    </main>
    </div>
</template>

<script>
import NavComp from '@/components/Nav.vue' 
import HeaderComp from '@/components/Header.vue' 

export default {
  components: {
    NavComp,
    HeaderComp
  }

}
</script>

<style src="./assets/css/style.css">
</style>
