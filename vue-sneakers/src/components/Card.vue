<template>
  <div class="">
        <div class="relative bg-white border border-slate-100 rounded-3xl p-8 cursor-pointer transition hover:-translate-y-2 hover:shadow-xl">
           <img :src="!isfavorite ? '/like-1.svg' : '/like-2.svg' " alt="" class="absolute top-8 left-8">
           <img :src="imageUrl" alt="">
           <p class="mt-2">{{ title }}</p>
           <div class="flex justify-between mt-5">
              <div class="flex flex-col">
                  <span class="text-slate-400">Цена</span>
                  <b>{{ price }} руб</b>
              </div>

              <img :src="!isAdded ? '/plus.svg' : '/checked.svg' "  alt="">
           </div>
        </div>
    </div>
</template>

<script setup>
defineProps({
    imageUrl:String,
    title:String,
    price:Number,
    isfavorite: Boolean,
    isAdded:Boolean,
    onclickAdd : Function,
    onclickFavorite:Function
})

</script>

<style>

</style>