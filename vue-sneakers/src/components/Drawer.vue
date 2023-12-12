<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
  <div class="bg-white w-96 h-full fixed right-0 top-0 z-20 p-8">
        <div class="flex items-center gap-5 mb-8">
            <svg class="rotate-180 opacity-30 hover:opacity-100" width="16" height="14" viewBox="0 0 16 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M1 7H14.7143" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                <path d="M8.71436 1L14.7144 7L8.71436 13" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        <h2 class="text-2xl font-bold">Корзина </h2>
      </div>
        <card-item-list/>

        <div class="flex flex-col gap-4 mb-6">
            <div class="flex gap-2">
                <span>Итого</span>
                <div class="flex-1 border-b border-dashed"></div>
                <b>12990 руб</b>
            </div>
            <div class="flex gap-2">
                <span>Налог 5%</span>
                <div class="flex-1 border-b border-dashed"></div>
                <b>990 руб</b>
            </div>
            <button disabled class="bg-lime-500 w-full rounded-xl py-3 text-white hover:bg-lime-600 transition disabled:bg-slate-300">
              Оформить заказ
            </button>
        </div>
      

        
  </div>
</template>

<script>
import CardItemList from './CardItemList.vue'

export default {
  components: {CardItemList  },

}
</script>

<style>

</style>