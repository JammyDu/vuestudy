
<template>
  <div>
    <h1 @click="add">{{count}}</h1>
  </div>
</template>

<script setup>
import { ref } from "vue";
let count = ref(1)
function add(){
    count.value++
}
</script>

<style>
  color: red;
}
</style>