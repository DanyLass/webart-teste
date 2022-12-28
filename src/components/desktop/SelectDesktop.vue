
<template>
    <select v-model="selected" id="select-number">
        <option disabled value=""></option>
        <option>1</option>
        <option>2</option>
        <option>3</option>
    </select>
</template>
<script>
export default {
    name: "SelectDesktop"
}
</script>

<style scoped>
#select-number {
    display: flex;
    width: 45px;
    height: 40px;
    color: #8c8787;
    text-align: center;
    border-color: #e1d8d8;
    border-radius: 4px;
    box-shadow: 1px 1px 1px 1px #e1d8d8;
    background-color: #fff;
    outline: none;

}
</style>