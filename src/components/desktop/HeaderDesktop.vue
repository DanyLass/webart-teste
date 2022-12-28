<template>
    <container id="header-desktop-container">
        <div id="img">
            <img alt="Web logo" id="header-image" src="../../assets/logo.jpg">
        </div>
        <InputDesktop />
        <div id="header-text">
            <h3>Olá, bem vindo(a)!</h3>
            <p id="header-line">Entre ou cadastre-se</p>
        </div>
        <h4>Meu carrinho</h4>
        <div id="listen-container">
            <ul id="listen-icons">
                <li>Ar Condicionado</li><img alt="icons" id="icons" src="../../assets/icons/icon-ar.jpg" />
                <li>Eletrodomésticos</li>
                <li>Eletroportáteis</li>
                <li>Comércio e Industria</li>
                <li>Peças</li>
                <li>Máquinas e Ferramentas</li>
                <li>Natal</li>
            </ul>
        </div>
    </container>
</template>

<script>
import InputDesktop from '../desktop/InputDesktop.vue';
export default {
    name: 'HeaderDesktop',
    components: {
        InputDesktop,
    }
}
</script>

<style scoped>
container {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    margin: 20px;
    padding-left: 200px;
}

#header-image {
    display: flex;
}

#header-line {
    display: flex;
    align-items: center;
    margin-left: 10px;
    font-size: 15px;
    text-decoration: underline;
}

#header-desktop-container {
    display: flex;
    justify-content: space-around;




}

#header-text {
    justify-content: center;
    align-items: center;
    margin-right: 500px;

}

h3 {
    display: flex;
    width: 100%;
    color: #ff4f01;
    margin-left: 10px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

h4 {
    display: flex;
    width: 100%;
    color: #ff4f01;
}

#listen-container {
    width: 100%;


}

#listen-icons {
    display: flex;
    margin-top: 100px;
    background-color: #ff4f01;

}
</style>