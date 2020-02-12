<template>
    <b-menu class="dash">
      <div class="icon-back">
        <div class="gradient-color-overlay"></div>
      </div>
        <b-menu-list>
            <div>
              <img style="position:absolute;margin-left:11px;margin-top:5px;" src="../assets/home.svg"/>
              <b-menu-item class="itens-text" label="Painel"></b-menu-item>
            </div>
            <div>
              <img class="img-item" src="../assets/file.svg"/>
              <b-menu-item class="itens-text" label="Minhas Redações"></b-menu-item>
            </div>
            <div>
              <img class="img-item" src="../assets/propostas.svg"/>
              <b-menu-item class="itens-text" label="Propostas"></b-menu-item>
            </div>
            <div>
              <img class="img-item" src="../assets/simulado.svg"/>
              <b-menu-item class="itens-text" label="Simulados"></b-menu-item>
            </div>
        </b-menu-list>
        <b-menu-list label="BIBLIOTECA">
            <div>
              <img class="img-item" src="../assets/videoaulas-1.svg"/>
              <b-menu-item class="itens-text" style="margin-top:-5px;" label="Videoaulas"></b-menu-item>
            </div>
            <div>
              <img class="img-item" src="../assets/materiais-1.svg"/>
              <b-menu-item class="itens-text" label="Materiais"></b-menu-item>
            </div>
            <div>
              <img class="img-item" src="../assets/coletaneas-1.svg"/>
              <b-menu-item class="itens-text" label="Coletâneas"></b-menu-item>
            </div>
            <div>
              <img class="img-item" src="../assets/folha_redacao-1.svg"/>
              <b-menu-item class="itens-text" label="Folhas de Redação"></b-menu-item>
            </div>
            <div>
              <img class="img-item" src="../assets/tutoriais-1.svg"/>
              <b-menu-item class="itens-text" label="Tutoriais"></b-menu-item>
            </div>
            <div style="margin-top:295px;">
              <img class="img-item" src="../assets/upload.svg"/>
              <b-menu-item class="itens-text" label="Nova Redação"></b-menu-item>
            </div>
        </b-menu-list>
    </b-menu>
</template>
<style>
  .img-item{
    position: absolute;
    margin-left: 15px;
    margin-top: 5px;
  }
  .itens-text{
    font-size: 15px;
    margin-left: 40px;
  }
  .dash{
    width: 33.33vh;
    height: 100vh;
    text-align: start !important;
    box-shadow: 3px 0px 5px 0px #00000026;
  }
  .gradient-color-overlay{
    width: 100%;
    height: 100%;
    background: linear-gradient(114deg, rgb(235, 174, 29), rgb(234, 87, 3), rgb(217, 0, 15));
    opacity: .7;
  }
  .icon-back{
    background: rgb(228, 139, 88) url("../assets/logo-dash-small.png") no-repeat;    height: 100px;
    width: 33.33vh;
    display: flex;
    background-position-x: center;
  }
</style>