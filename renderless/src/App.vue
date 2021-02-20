<template>
  <div>
    <fetch-data url="https://jsonplaceholder.typicode.com/users/1"></fetch-data>
    <div slot-scope="{ response , loading }">
      <div  v-if="!loading">
        {{ response.name }}
      </div>
      <div v-if="loading">
        loading...
      </div>
    </div>
  </div>
</template>

<script>
// import FetchData from './components/FetchData.vue';
import FetchData from './components/FetchData.vue'

export default{
  components: {
    FetchData
  }
}
</script>

<style scoped>

</style>