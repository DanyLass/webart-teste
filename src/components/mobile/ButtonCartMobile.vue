<template>
   <div id="button-container">
      <button class="button" id="button" @mouseover="isHovering = true" @mouseleave="isHovering = false"><img
            alt="icons" id="cart-icon" src="../../assets/icons/cart-shopping.svg" />Adicionar ao
         carrinho</button>
   </div>
</template>

<script>

export default {
   name: "ButtonCartMobile",
   data() {
      return {
         isHovering: false
      }

   }
}

</script>

<style scoped>
button {
   border: none;
   display: flex;
   align-items: center;
   justify-content: center;
   width: 100%;
   height: 40px;
   background-color: #06cc84;
   border-radius: 5px;
   color: #FFF;
   font-size: 15px;
   font-family: sans-serif;
}

.button:hover {
   background-color: #038354;
}

#button-container {
   padding-bottom: 10px;
   padding-top: 10px;
   margin-right: 12px;
}

#cart-icon {
   width: 30px;
   padding-bottom: 5px;
   margin-left: 11px;
}
</style>