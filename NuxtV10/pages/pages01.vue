<template>
  <div class="">
    <h1>{{demo}}</h1>
   <h1 v-for="(data , index ) in news " :key="index">{{data}} </h1>
  </div>
</template>

<script>
export default {
    data() {
        return {
            demo: 'Hello',
             news: [1,2,3,4,5],
        }
    },
}
</script>

<style>

</style>