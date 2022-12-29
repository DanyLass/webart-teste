<template>
    <container id="input-desktop-container">
        <div id="input-wrapper">
            <input type="text" v-model="input_name" placeholder="Procure por produtos, marcas ou nomes... "
                id="input-search" />
            <button class="button" id="search-button"> <img alt="icons" id="image-search"
                    src="../../assets/icons/buscar.jpg" /></button>
        </div>
    </container>
</template>
      
<script>

export default {
    name: "InputDesktop",
}
</script>
  
<style scoped>
container {
    width: 100%;
}

#input-desktop-container {
    display: flex;
    width: 100%;
    margin-right: 80px;
    padding-left: 1px;
}

#input-wrapper {
    display: flex;
    width: 100%;
}

#input-search {
    width: 100%;
    height: 50px;
    font-size: 18px;
    border-radius: 8px 0px 0px 8px;
    border-color: #EEE9E9;
    padding-left: 15px;
    outline: none;
}

#search-button {
    display: flex;
    width: 40px;
    height: 51px;
    border-top-right-radius: 8px;
    border-bottom-right-radius: 8px;
    align-items: center;
    justify-content: center;
    outline: none;
}

#image-search {
    width: 50px;
    height: 51px;
}
</style>
