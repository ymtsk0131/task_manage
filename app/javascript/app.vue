<template>
  <div>
    <router-view></router-view>
  </div>
</template>

<script>
import Vue from 'vue'
import VueRouter from 'vue-router'
import Home from 'components/pages/Home.vue'

const router = new VueRouter({
  routes: [
    { path: '/', component: Home }
  ]
})

Vue.use(VueRouter)

export default {
  router
}
</script>

<style scoped>
</style>
