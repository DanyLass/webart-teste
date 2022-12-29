<template>
    <div class="dropdown">
        <span id="title"><img alt="icons" id="icon-menu" src="../../assets/icons/menuIcon.svg" />Ver toda a
            Loja</span>
        <div class="dropdown-content" id="dropdown-listen">
            <p>Ar Condicionado<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" /></p>
            <p>Ventilação<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" /></p>
            <p>Eletrodoméstico<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" /></p>
            <p>Eletroportáteis<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" /></p>
            <p>Casa Inteligente<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" /></p>
            <p>Comércio e Indústria<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" /></p>
            <p>Máquinas e Ferramentas<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" />
            </p>
            <p>Materiais e Instalação<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" />
            </p>
            <p>Fluído Gás Refrigerante<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" />
            </p>
            <p>Peças<img alt="icons" id="icon-chevron" src="../../assets/icons/chevron-right.svg" /></p>
        </div>
    </div>
</template>

<script>

export default {
    name: 'DropdownDesktop'
}

</script>

<style scoped>
.dropdown {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #ffff;
    min-width: 200px;
    min-height: 600px;
    padding: 30px 35px;
    border-radius: 3px;
    border: 1px solid #d8d0d0;
    z-index: 1;
    color: #8c8787;

}

.dropdown:hover .dropdown-content {
    display: block;
}

#title {
    width: 250px;
    height: 70px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #ff4f01;
    font-family: sans-serif;
    font-weight: bold;
    background-color: #fff;
}

#dropdown-listen {
    border: 2px solid #d8d0d0;
    margin-right: 10px;
    font-size: 0.9rem;
    float: left;
    height: 30px;
    line-height: 30px;
    margin: 5% auto;
}

#icon-menu {
    width: 30px;
    margin-right: 10px;
}

p {
    display: flex;
    justify-content: space-between;
}
</style>