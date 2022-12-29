<template>
    <container id="header-desktop-container">
        <div id="header-content">
            <div id="header">
                <div id="img">
                    <img alt="Web logo" id="header-image" src="../../assets/logo.jpg">
                </div>
                <InputDesktop />
                <div id="header-text">
                    <h3>Olá, bem vindo(a)!</h3>
                    <p id="header-line">Entre ou cadastre-se</p>
                </div>
                <h4>Meu carrinho</h4>
            </div>
            <div id="products-list">
                <DropdowntDesktop />
                <li id="product-list-item"> <img alt="icons" id="icons" src="../../assets/icons/icon-ar.jpg" /> Ar
                    Condicionado</li>
                <hr id="divider" />
                <li id="product-list-item"><img alt="icons" id="icons" src="../../assets/icons/icon-eletro.jpg" />
                    Eletrodomésticos </li>
                <hr id="divider" />
                <li id="product-list-item"> <img alt="icons" id="icons" src="../../assets/icons/icon-eletro2.jpg" />
                    Eletroportáteis</li>
                <hr id="divider" />
                <li id="product-list-item"> <img alt="icons" id="icons" src="../../assets/icons/industria.jpg" />
                    Comércio e Industria</li>
                <hr id="divider" />
                <li id="product-list-item"> <img alt="icons" id="icons" src="../../assets/icons/icon-pecas.jpg" />
                    Peças</li>
                <hr id="divider" />
                <li id="product-list-item"> <img alt="icons" id="icons" src="../../assets/icons/icon-ferramentas.jpg" />
                    Máquinas e Ferramentas</li>
                <hr id="divider" />
                <li id="product-list-item"> <img alt="icons" id="icons"
                        src="../../assets/icons/arvore-de-natal-50 (1).png" />Natal</li>
            </div>
        </div>
    </container>
</template>

<script>
import InputDesktop from '../desktop/InputDesktop.vue';
import DropdowntDesktop from '../desktop/DropdownDesktop.vue';
export default {
    name: 'HeaderDesktop',
    components: {
        InputDesktop,
        DropdowntDesktop,
    }
}
</script>

<style scoped>
container {
    width: 100%;
    height: 100%;
}

#header-content {
    width: 100%;
}

#header {
    display: flex;
    align-items: center;
    padding-top: 15px;
}

#header-image {
    display: flex;
    margin-left: 230px;
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
    margin-right: 50px;
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

#products-list {
    width: 100%;
    margin-top: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #ff4f01;
}

#icons {
    width: 20px;
    height: 20px;
    margin: 4px
}

#product-list-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: 0 8px 0;
    color: #fff;
    padding: 10px;
}

#divider {
    border-left: 2px solid #250dd9;
    height: 50px;
}
</style>