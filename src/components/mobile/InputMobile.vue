<template>

    <container>
        <header>
            <div id="input-wrapper">
                <input type="text" v-model="input_name" placeholder="Procure por produtos, marcas ou nomes... "
                    id="input-search" />
                <button class="btn" id="search-button"> <img alt="icons" id="menu-search"
                        src="../../assets/icons/buscar.jpg" /></button>
            </div>
        </header>
    </container>
</template>
      
<script>

export default {
    name: "InputMobile",
}
</script>
  
<style scoped>
#input-wrapper {
    display: flex;
    justify-content: center;
    padding-bottom: 10px;

}

#input-search {
    Width: 80%;
    height: 40px;
    font-size: 15px;
    border-radius: 8px 0px 0px 8px;
    border-color: #EEE9E9
}

#search-button {
    display: flex;
    width: 40px;
    height: 40px;
    border-top-right-radius: 8px;
    border-bottom-right-radius: 8px;
    align-items: center;
    justify-content: center;
}

#menu-search {
    width: 40px;
    height: 41px;
}
</style>
