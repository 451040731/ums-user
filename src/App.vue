<template>
  <div id="app">
    <Loading></Loading>
    <router-view></router-view>
  </div>
</template>

<script>
 import Loading from './components/Loading'

export default {
  name: 'App',
  components: {
    Loading
  }
}
</script>

<style lang="scss" scoped>
</style>
