<template>
  <header class="flex justify-between border-b border-slate-200 px-10 py-8">
      <div class="flex items-center gap-4">
         <img src="/logo.png" alt="Logo" class="w-10">
         <div>
          <h2 class="text-xl font-bold uppercase">Vue sneakers</h2>
          <p class="text-slate-400">Магазин лучших кросовок</p>
         </div>
      </div>
      <ul class="flex items-center gap-10">
        <li class="flex items-center gap-3 text-gray-400 hover:text-black cursor-pointer">
          <img src="/cart.svg" alt="">
          <b>1205 руб</b>
        </li>
        <li class="flex items-center gap-3 text-gray-400 hover:text-black cursor-pointer">
          <img src="/heart.svg" alt="">
          <span>Закладки</span>
        </li>
        <li class="flex items-center gap-3 text-gray-400 hover:text-black cursor-pointer">
          <img src="/profile.svg" alt="">
          <span>Профиль</span>
        </li>
      </ul>

    </header>
</template>

<script>
export default {

}
</script>

<style>

</style>