<template>
  <Drawer/>
  <div class="bg-white rounded-xl shadow-xl mt-14  w-4/5 m-auto">
    <Header/>
    <div class="p-10">
      <div class="flex justify-between">
        <h2 class="text-3xl font-bold mb-8">Все кроссовки</h2>
        <div>
            <input type="text">
        </div>
      </div>
    <card-list/>
   </div>
    
  </div>
</template>



<script setup>
import CardList from './components/CardList.vue';
import Header from './components/Header.vue'
import Drawer from './components/Drawer.vue';

</script>



<style scoped>

</style>
