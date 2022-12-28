<template>
    <container>
        <header>
            <HeaderDesktop />
        </header>
        <content>
            <div id="home-text-content">
                <img alt="img" id="topo-image" src="../assets/destaque-topo.png" />
                <div id="text-content">
                    <h2>Eletrodomésticos</h2>
                    <p id="text-info">
                        Você consegue imaginar sua rotina sem os eletrodomésticos? Difícil, né? Eles são equipamentos
                        essenciais
                        para realizar as tarefas domésticas com praticidade e eficiência, além de oferecer conforto para
                        o
                        seu
                        lar. Aqui na Dufrio você encontra diversas opções de eletrodomésticos para a cozinha, a
                        lavanderia e
                        outros ambientes da casa.<span id="line-bold">Confira as nossas dicas de compra de
                            eletrodomésticos
                            na
                            Dufrio!</span></p>
                </div>
            </div>
            <div id="button-number">
                <h6>Itens por página:</h6>
                <SelectDesktop />
                <h7> Ordenar por:</h7>
                <SelectDesktopOrdenation />
            </div>

            <div id="items-content">
                <aside class="column side" id="listen-category">
                    <h4>Categorias</h4>
                    <div class="text" id="products">Champanheira Elétrica</div>
                    <div class="text" id="products">Churrasqueira</div>
                    <div class="text" id="products">Coifa</div>
                    <div class="text" id="products">Cooktop</div>
                    <div class="text" id="products">Depurador de Ar</div>
                    <div class="text" id="products">Fogão a Gás</div>
                    <div class="text" id="products">Forno a Gás</div>
                    <div class="text" id="products">Forno Elétrico</div>
                    <div class="text" id="products">Frigobar</div>
                    <button id="button-category">Ver mais</button>
                </aside>

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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
                    </div>
                    <div id="grid-item">
                        <img alt="img" id="grid-image" src="../assets/produtos/Refrigerador.jpg" />
                        <label type="text" id="percentage">-23%</label>
                        <p id="text">Geladeira/Refrigerador Electrolux Degelo Prático 240 Litros
                            Cycle Defrost Branco RE31
                            220v
                        </p>
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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
                    </div>
                    <div id="grid-item">
                        <div>
                            <img alt="img" id="grid-image"
                                src="../assets/produtos/forno-eletrico-continental-44l.jpg" />
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
                        <ButtonCartDesktop />
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
                        <ButtonCartDesktop />
                    </div>
                </div>
            </div>
        </content>
        <footer>
            <div id="buttons-container">
                <h6>Produtos: 1-12 e 284 encontrado(s)</h6>
                <button class="button" id="chevron-button" @mouseover="isHovering = true"
                    @mouseleave="isHovering = false"> <img alt="icons" id="chevron-left"
                        src="../assets/icons/arrow-left.svg" />Primeira</button>
                <button class="button" id="chevron-button"> <img alt="icons" id="chevron-left"
                        src="../assets/icons/chevron-left.svg" />Anterior</button>
                <button class="button" id="button-page">1</button>
                <button class="button" id="button-page">2</button>
                <button class="button" id="button-page">3</button>
                <button class="button" id="button-page">4</button>
                <button class="button" id="button-page">5</button>
                <button class="button" id="chevron-button">Próximo <img alt="icons" id="chevron-right"
                        src="../assets/icons/chevron-right.svg" /></button>
                <button class="button" id="chevron-button">Última<img alt="icons" id="chevron-right"
                        src="../assets/icons/arrow-right.svg" /></button>
            </div>
            <div>
                <p id="text-end"> 2022-Todos os direitos reservados | TESTE PARA DESENVOLVEDOR ASSISTENTE
                    FRONTEND|CNPJ:00.000.000/0000-00 BIRIGUI - SP </p>
            </div>
            <div id="logo">
                <img alt="Web logo" id="logo-img" src="../assets/logo.jpg">
            </div>
        </footer>
    </container>
</template>

<script>
import HeaderDesktop from '../components/desktop/HeaderDesktop.vue';
import SelectDesktop from '../components/desktop/SelectDesktop.vue';
import SelectDesktopOrdenation from '../components/desktop/SelectDesktopOrdenation.vue';
import ButtonCartDesktop from '../components/desktop/ButtonCartDesktop.vue';

export default {
    name: "HomeDesktop",
    components: {
        HeaderDesktop,
        SelectDesktop,
        ButtonCartDesktop,
        SelectDesktopOrdenation,
    },
    data() {
        return {
            isHovering: false
        }
    },
}
</script>

<style scoped>
container {
    width: 100%
}

#topo-image {
    display: flex;
    justify-content: center;
    align-content: center;
    padding-left: 220px;
}

#home-text-content {
    width: 100%;
    display: flex;
    align-items: center;
    background-color: var(--color-background-banner);
    margin-top: 100px;
    padding-bottom: 10px;
    padding-top: 10px;
    border-bottom: 2px solid #1E90FF;
}

#text-content {
    display: block;
}

#text-info {
    display: block;
    text-align: justify;
    line-height: 25px;
    color: #8c8787;
    font-size: 18px;
    padding: 8px;
    margin-right: 20rem;
    margin-left: 10rem;
}

h2 {
    width: 100%;
    display: flex;
    align-items: center;
    padding-left: 10.5rem;
    color: #ff4f01;
    font-size: 30px
}

#line-bold {
    font-weight: bold;
}

#button-number {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    margin-top: 30px;
    padding-right: 30rem;
    margin-right: 10px;
}

#items-content {
    display: flex;
    justify-content: right;
    margin-right: 30px;
    padding-top: 30px;
}

#grid {
    display: grid;
    grid-template-columns: repeat(3, 20%);
    place-items: center;
    justify-content: center;
}

#grid-item {
    display: flex;
    align-items: center;
    flex-direction: column;
    align-content: center;
}

#grid-image {
    width: 100%;
}

#percentage {
    background-color: #000;
    color: #fff;
    width: 60px;
    height: 25px;
    border-radius: 5px;
    margin-right: 210px;
    padding-top: 4px;
    padding-left: 10px;
    font-weight: bold;
}

#text {
    color: #8c8787;
    text-align: center;
    justify-content: center;
    font-family: sans-serif;
    font-size: 0.9rem;
    margin: 15px;
}

#stamp {
    width: 45%;
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
    width: 85px;
    height: 80px;
    position: absolute;
}

h3 {
    text-align: center;
    color: #1E90FF;
    font-family: sans-serif;
    font-size: 1.5rem;
}

h5 {
    color: #1E90FF;
    text-align: center;
    font-family: sans-serif;
    font-size: 0.8rem;
}

#line {
    color: #8c8787;
    text-align: center;
    font-family: sans-serif;
    font-size: 0.8rem;
}

h6 {
    font-size: 0.9rem;
    color: #8c8787;
    margin-right: 20px;
}

h7 {
    font-size: 1rem;
    color: #8c8787;
    margin-right: 6px;
    font-weight: bold
}

#buttons-container {
    display: flex;
    width: 100%;
    align-items: center;
    justify-content: center;
    flex-direction: row;
    padding-bottom: 20px;
    padding-top: 30px;
    margin-left: 130px;
}

#chevron-button {
    display: flex;
    border: 1px solid #d7d0d0;
    background-color: #fff;
    align-items: center;
    border-radius: 4px;
    padding: 10px;
    margin-left: 10px;
    color: #8c8787;
    font-size: 1rem
}

#button-page {
    width: 2%;
    display: flex;
    background-color: #fff;
    align-items: center;
    color: #8c8787;
    border: 1px solid #d7d0d0;
    border-radius: 4px;
    padding: 10px;
    padding-right: 5px;
    margin-left: 8px;
}

.button:hover {
    opacity: 0.3
}

#chevron-left,
#chevron-right {
    width: 15px;
    height: 18px;
}

#text-end {
    display: flex;
    padding: 10px;
    margin-right: 100px;
    text-align: center;
    justify-content: center;
    font-family: sans-serif;
    font-weight: bold;
    font-size: 13px;
    color: #8c8787
}

#logo {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 70%;
    padding-top: 5px;
    padding-bottom: 10px;
    margin-left: 250px;
}

#logo-img {
    width: 10%
}

footer {
    margin-top: 50px;
    flex-direction: column;
    width: 100%;
    align-items: center;
    justify-content: center;
}

h4 {
    display: flex;
    align-items: center;
    color: #ff4f01;
    font-size: 1.5rem;
}

#listen-category {
    width: 100px;
    color: #8c8787;
    margin-left: 80px;

}

#button-category {
    width: 100px;
    font-size: 1.2rem;
    background: #fff;
    border: none;
    color: #8c8787;
    margin-top: 10px;
    padding-right: 25px;
}

#products {
    font-size: 1.2rem;
}

@media (min-width: 320px) and (max-width: 1096px) {
    container {
        display: none
    }
}
</style>
