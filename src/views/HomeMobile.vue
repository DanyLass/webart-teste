<template>
    <container>
        <header>
            <HeaderMobile />
        </header>
        <content>
            <button class="button" id="chevron"> <img alt="icons" id="icon-chevron"
                    src="../assets/icons/chevron-left.svg" />
                <strong>Eletrodomésticos</strong>
            </button>
            <div id="content-top">
                <img alt="img" id="topo" src="../assets/destaque-topo.png" />
                <h2>Eletrodomésticos</h2>
                <p id="text-info">
                    Você consegue imaginar sua rotina sem os eletrodomésticos? Difícil, né? Eles são equipamentos
                    essenciais
                    para realizar as tarefas domésticas com praticidade e eficiência, além de oferecer conforto para o
                    seu
                    lar. Aqui na Dufrio você encontra diversas opções de eletrodomésticos para a cozinha, a lavanderia e
                    outros ambientes da casa.<span id="line-bold">Confira as nossas dicas de compra de eletrodomésticos
                        na
                        Dufrio!</span></p>
                <div id="button-read">
                    <button id="read">Leia mais ></button>
                </div>
            </div>
            <div id="button-filter">
                <button id="filter">Filtrar</button>
            </div>
            <hr />
            <div id="grid">
                <div id="grid-item">
                    <img alt="img" id="grid-image" src="../assets/produtos/forno-embutido.jpg" />
                    <label type="text" id="percentage">-21%</label>
                    <p id="text">Forno a Gás de Embutir
                        Venax Bianco 90 Litros Branco</p>
                    <img alt="img" id="stamp" src="../assets/selos/venax.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$1.499,13</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$1.665,70 em 10x de R$166,57 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <img alt="img" id="grid-image" src="../assets/produtos/forno-embutido-50l.jpg" />
                    <label type="text" id="percentage">-21%</label>
                    <p id="text">Forno a Gás de Embutir
                        Venax Arena Eg Gll 50 Litros Grill Inox</p>
                    <img alt="img" id="stamp" src="../assets/selos/venax.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$1.410,72</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$1.567,47 em 10x de R$156,75 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <img alt="img" id="grid-image" src="../assets/produtos/micro-ondas.jpg" />
                    <label type="text" id="percentage">-28%</label>
                    <p id="text">Micro-ondas LG Solo 30 Litros Preto MS3097
                    </p>
                    <img alt="img" id="stamp" src="../assets/selos/lg.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$649,00</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$721,11 em 10x de R$72,11 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <img alt="img" id="grid-image" src="../assets/produtos/Refrigerador.jpg" />
                    <label type="text" id="percentage">-23%</label>
                    <p id="text">Geladeira/Refrigerador Electrolux Degelo Prático 240 Litros
                        Cycle Defrost Branco RE31
                        220v
                    </p>
                    <!-- <img alt="img" id="star" src="../../assets/icons/avaliacao.png" /> -->
                    <img alt="img" id="stamp" src="../assets/selos/electrolux.png" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$1.890,52</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$2.100,58 em 10x de R$210,06 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <img alt="img" id="grid-image" src="../assets/produtos/maquina-lavar-11kl.jpg" />
                    <label type="text" id="percentage">-20%</label>
                    <p id="text">Lava e Seca LG VC5 11kg Branca CV3011WG4A
                    </p>
                    <img alt="img" id="stamp-" src="../assets/selos/lg.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$3.500,99</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$3.889,99 em 10x de R$389,00 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <img alt="img" id="grid-image" src="../assets/produtos/forno-eletrico-45l.jpg" />
                    <label type="text" id="percentage">-21%</label>
                    <p id="text">Forno Elétrico de Embutir Venax Grand Gourmet 45 litros Preto
                    </p>
                    <img alt="img" id="stamp" src="../assets/selos/venax.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$793,24</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$881,38 em 10x de R$88,14 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">

                    <img alt="img" id="grid-image" src="../assets/produtos/refrigerador-french.jpg" />
                    <label type="text" id="percentage">-20%</label>
                    <p id="text">Geladeira/Refrigerador French Door 525L Preto GR-X228NMSM
                    </p>
                    <img alt="img" id="stamp" src="../assets/selos/lg.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$18.266,10</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$20.295,67 em 10x de R$2.029,57 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <div>
                        <img alt="img" id="stamp-transport" src="../assets/selos/frete-gratis.png" />
                        <img alt="img" id="grid-image" src="../assets/produtos/maquina-lavar-14kl.jpeg" />
                    </div>
                    <label type="text" id="percentage">-23%</label>
                    <p id="text">Lava e Seca LG Smart 14kg Branca WD14WGSP6-220v
                    </p>
                    <img alt="img" id="stamp" src="../assets/selos/lg.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$4.760,90</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$5.289,89 em 10x de R$528,99 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <div>
                        <img alt="img" id="stamp-transport" src="../assets/selos/frete-gratis.png" />
                        <img alt="img" id="grid-image" src="../assets/produtos/coifa-fogatti-90cm.png" />
                    </div>
                    <label type="text" id="percentage">-32%</label>
                    <p id="text">Coifa de parede Fogatti Slim 90cm Vidro Curvo Inox
                    </p>
                    <img alt="img" id="stamp" src="../assets/selos/fogatti.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$599,00</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$665,56 em 10x de R$66,56 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <div>
                        <img alt="img" id="stamp-transport" src="../assets/selos/frete-gratis.png" />
                        <img alt="img" id="grid-image" src="../assets/produtos/microondas-32l.jpg" />
                    </div>
                    <label type="text" id="percentage">-21%</label>
                    <p id="text">Micro-Ondas Consul 32 litros Branco CMS46AB
                    </p>
                    <img alt="img" id="stamp" src="../assets/selos/consul.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$617,08</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$685,64 em 10x de R$68,56 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <div>
                        <img alt="img" id="grid-image" src="../assets/produtos/forno-eletrico-continental-44l.jpg" />
                    </div>
                    <label type="text" id="percentage">-20%</label>
                    <p id="text">Forno Elétrico Continental 44 Litros grill Branco BC44B
                    </p>
                    <img alt="img" id="stamp" src="../assets/selos/continental.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$775,34</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$861,49 em 10x de R$86,15 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
                <div id="grid-item">
                    <div>
                        <img alt="img" id="grid-image" src="../assets/produtos/coifa-fogatti-60cm.jpg" />
                    </div>
                    <label type="text" id="percentage">-21%</label>
                    <p id="text">Coifa de Parede Fogatti Slim Vidro Curvo Inox 60cm
                    </p>
                    <img alt="img" id="stamp" src="../assets/selos/fogatti.jpg" />
                    <div id="item-selos">
                        <img alt="img" id="stamp-selos" src="../assets/selos/procel.jpg" />
                        <img alt="img" id="stamp-selos" src="../assets/selos/voltagem.jpg" />
                    </div>
                    <div>
                        <h3>R$675,91</h3>
                        <h5> à vista no PIX ou boleto</h5>
                        <p id="line"> ou R$751,01 em 10x de R$75,10 sem juros</p>
                    </div>
                    <ButtonCartMobile />
                </div>
            </div>
        </content>
        <footer>
            <h6>Produtos: 1-12 e 284 encontrado(s)</h6>
            <div id="buttons-container">
                <button class="button" id="chevron-button"> <img alt="icons" id="chevron-left"
                        src="../assets/icons/chevron-left.svg" /></button>
                <button class="button" id="button-page">1</button>
                <button class="button" id="button-page">2</button>
                <button class="button" id="button-page">3</button>
                <button class="button" id="button-page">4</button>
                <button class="button" id="button-page">5</button>
                <button class="button" id="chevron-button"> <img alt="icons" id="chevron-right"
                        src="../assets/icons/chevron-right.svg" /></button>
            </div>
            <div>
                <p id="text-end"> 2022-Todos os direitos reservados | TESTE PARA DESENVOLVEDOR ASSISTENTE
                    FRONTEND|CNPJ:00.000.000/0000-00 BIRIGUI - SP </p>
            </div>
            <div id="logo">
                <img alt="Web logo" src="../assets/logo.jpg">
            </div>
        </footer>
    </container>
</template>

<script>
import HeaderMobile from "../components/mobile/HeaderMobile.vue"
import ButtonCartMobile from "../components/mobile/ButtonCartMobile.vue";
export default {
    name: 'HomeMobile',
    components: {
        HeaderMobile,
        ButtonCartMobile,
    }
}
</script>

<style scoped>
container {
    display: flex;
    flex-direction: column;
}

#content {

    background-color: #edf5f8;
    padding: 10px;
}

#content-top {
    background-color: var(--color-background-banner);
}

#chevron {
    display: flex;
    align-items: center;
    border: none;
    background-color: #fff;
    margin-top: 10px;
    padding-bottom: 10px;
}

#icon-chevron {
    width: 18px;
}

strong {
    color: #8c8787;
    font-family: sans-serif;
    font-size: 12px;
}

img {
    width: 100%;
}

h2 {
    padding-bottom: 5px;
    padding-top: 10px;
    text-align: center;
    color: #ff4f01;
    font-size: 30px
}

#text-info {
    text-align: justify;
    line-height: 22px;
    color: #8c8787;
    font-size: 15px;
    padding: 8px;
}

#line-bold {
    font-weight: bold;
}

h4 {
    text-align: justify;
    line-height: 22px;
    color: #8c8787;
    font-size: 15px;
    padding: 8px;
}

#button-read {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 20px;

}

#read {
    background-color: #ff4f01;
    width: 330px;
    height: 30px;
    border-radius: 3px;
    color: #fff;
    border: none;
}

#button-filter {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 20px;
    padding-bottom: 20px;

}

#filter {
    background-color: #ff4f01;
    width: 330px;
    height: 40px;
    border-radius: 3px;
    color: #fff;
    border: none;

}

#percentage {
    background-color: #000;
    color: #fff;
    width: 50px;
    height: 20px;
    font-size: 13px;
    border-radius: 3px;
    margin-right: 90px;
    margin-top: 20px;
    padding-top: 3px;
}

#grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    text-align: center;
    width: 100%;
    justify-content: center;

}

#grid-item {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 10px;
    border-bottom: 1px solid #CCC;
    border-right: 1px solid #CCC;
}

#text {
    color: #8c8787;
    text-align: center;
    font-family: sans-serif;
    font-size: 0.78rem;
    margin: 10px;
}

h5 {
    color: #1E90FF;
    text-align: center;
    font-family: sans-serif;
    font-size: 0.7rem;
}

#line {
    color: #8c8787;
    text-align: center;
    font-family: sans-serif;
    font-size: 0.7rem;
}

#grid-image {
    width: 100%;

}

#stamp {
    width: 100%;
}

#item-selos {
    display: flex;
    justify-content: center;
    align-items: center;
}

#stamp-selos {
    width: 100%;
}

#stamp-transport {
    width: 50px;
    height: 50px;
    position: absolute;
}

h3 {
    text-align: center;
    color: #1E90FF;

    font-family: sans-serif;
}

/* #star {
    width: 80px;
    
} */

#text-end {
    display: flex;
    padding: 10px;
    text-align: center;
    justify-content: center;
    font-family: sans-serif;
    font-size: 12px;
    color: #8c8787
}

footer {
    display: flex;
    margin-top: 50px;
    flex-direction: column;
    width: 100%;
    align-items: center;
    justify-content: center;
}

h6 {
    text-align: justify;
    line-height: 2px;
    color: #8c8787;
    font-size: 12px;
    padding-top: 30px;
}

#buttons-container {

    display: flex;
    width: 100%;
    align-items: center;
    justify-content: center;
    flex-direction: row;
    padding-bottom: 20px;
    padding-top: 30px;
    margin-right: 10px;
}

#chevron-button {
    display: flex;
    border: 1px solid #d7d0d0;
    background-color: #fff;
    align-items: center;
    border-radius: 4px;
    padding: 12px;
    margin-left: 12px;
}

#button-page {
    display: flex;
    background-color: #fff;
    align-items: center;
    color: #8c8787;
    border: 1px solid #d7d0d0;
    border-radius: 4px;
    padding: 10px;
    margin-left: 8px;
}

#chevron-left,
#chevron-right {
    width: 20px;
    height: 20px;
}

#logo {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 30%;
    padding-top: 5px;
    padding-bottom: 10px;
}

@media (min-width: 1060px) {
    container {
        display: none
    }
}
</style>
