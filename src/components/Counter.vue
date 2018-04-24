<template>
  <div>
<h1>{{$store.state.count}}</h1>
  <button @click="$store.commit('add')">add</button>
  </div>
</template>
<script>
  import store from '@/vuex/store.js'
  export default{
    store
  }
</script>
<style scoped>

</style>
