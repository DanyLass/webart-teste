
<template>
    <select v-model="selected" id="select-ordernation">
        <option id="listem-select" disabled value=""></option>
        <option>Popularidade</option>
        <option>Menor Preço</option>
        <option>Maior Preço</option>
    </select>
</template>

<script>

export default {
    name: "SelectDesktopOrdernation",
}

</script>

<style scoped>
#select-ordernation {
    display: flex;
    width: 100px;
    height: 40px;
    color: #8c8787;
    text-align: center;
    border-color: #e1d8d8;
    border-radius: 4px;
    border-radius: 3px;
    box-shadow: 1px 1px 1px 1px #e1d8d8;
    background-color: #fff;
    font-size: 13px;
    outline: none;
}
</style>