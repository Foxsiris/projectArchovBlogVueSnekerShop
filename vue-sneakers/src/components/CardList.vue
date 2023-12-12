<template>
   <div class="grid grid-cols-4 gap-5">
     <card 
        imageUrl ="/sneakers/sneakers-5.jpg"
        price="5000"
        title="NameSneaker"
        isfavorite="false"
        :isAdded="true"
        :isfavorite="true"
    />
     <card/>
     <card/>
     <card/>
     <card/>
     <card/>
     <card/>
    </div>
</template>

<script>
import Card from './Card.vue'
export default {
  components: { Card },

}
</script>

<style>

</style>