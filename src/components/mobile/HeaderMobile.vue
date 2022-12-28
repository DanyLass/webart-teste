<template>
    <container>
        <header>
            <div id="items">
                <MenuButton />
                <div id="logo">
                    <img alt="Web logo" id="image-header" src="../../assets/logo.jpg">
                </div>
            </div>
            <div>
                <InputMobile />
            </div>
            <hr />
        </header>
    </container>
</template>

<script>
import InputMobile from '../../components/mobile/InputMobile.vue';
import MenuButton from '../MenuButton.vue';

export default {
    name: 'HeaderMobile',
    components: {
        InputMobile,
        MenuButton,
    }
}
</script>

<style scoped>
header {
    width: 100%;
}

#items {
    display: flex;
    margin-left: 18px;
}

hr {
    border: 0;
    border-bottom: 1px solid #CCC;
}

#logo {
    display: flex;
    justify-content: center;
    padding: 10px;
}

#image-header {
    display: flex;
    width: 100%;
}
</style>