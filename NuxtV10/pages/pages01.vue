<template>
  <div>
    <h1>{{data}}</h1>
  </div>
</template>

<script>
import {axios} from 'axios';
export default {

    data() {
        return {
            data : "Hi"
        }
    },
    mounted() {
        axios
    },
}
</script>

<style>

</style>