<template>
    <b-menu class="dash">
      <div class="icon-back">
        <div class="gradient-color-overlay"></div>
      </div>
        <b-menu-list>
            <div style="background-color: #F5B40026;">
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
        <b-menu-list label="BIBLIOTECA"><hr class="hr-label">
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
            <div style="margin-top:276px;height:50px;background-color:#ECECEC;">
              <img class="img-item" style="margin-top:17px;" src="../assets/upload.svg"/>
              <b-menu-item class="itens-text" style="margin-top:10px;" label="Nova Redação"></b-menu-item>
            </div>
        </b-menu-list>
    </b-menu>
</template>