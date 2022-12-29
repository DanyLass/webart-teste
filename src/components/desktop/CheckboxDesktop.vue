<template>
    <div>
        <div>
            <input type="checkbox" value="" v-model="status" /> <span>R$665,00 a R$5573,00</span>
        </div>
        <div>
            <input type="checkbox" value="" v-model="status" /> <span>R$5573,01 a R$10480,00</span>
        </div>
        <div>
            <input type="checkbox" value="" v-model="status" /> <span>R$10480,00 a 15388,00</span>
        </div>
        <div>
            <input type="checkbox" value="" v-model="status" /> <span>R$15388,01 a R$20295,00</span>
        </div>
        <div>
            <input type="checkbox" value="" v-model="status" /> <span>R$20295,01 a R$25203,00</span>
        </div>
    </div>
</template>

<script>

export default {
    name: 'CheckboxDesktop',
}
</script>

<style scoped>
span {

    font-size: 0.8rem;
}

input {
    font-size: 1rem;
    margin-top: 10px;
    margin-bottom: 5px;
}
</style>

