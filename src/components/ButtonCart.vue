<template>
   <div id="button-container">
      <button class="button" id="button" @mouseover="isHovering = true" @mouseleave="isHovering = false"><img
            alt="icons" id="cart-icon" src="../assets/icons/cart-shopping.svg" />Adicionar ao
         carrinho</button>
   </div>
</template>

<script>

export default {
   name: "ButtonCart",
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
   background-color: #42d481;
   border-radius: 5px;
   color: #FFF;
   font-size: 15px;
   font-family: sans-serif;
}

.button:hover {
   opacity: 0.7;
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