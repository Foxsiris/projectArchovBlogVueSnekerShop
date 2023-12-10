<template>
  <div class="bg-white rounded-xl shadow-xl mt-14  w-4/5 m-auto">
    <Header/>
    <div class="p-10">
    <h2 class="text-3xl font-bold mb-8">Все кроссовки</h2>
    <card-list/>
   </div>
    
  </div>
</template>



<script setup>
import CardList from './components/CardList.vue';
import Header from './components/Header.vue'

</script>



<style scoped>

</style>
