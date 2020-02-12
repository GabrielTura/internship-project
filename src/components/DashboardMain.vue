<template>
<div class="dashMain">
    <div class="library">
      <span class="library-title">Acesse A Biblioteca:</span>
        <div>
            <div class="div-icons">
                <div class="library-icons">
                    <img src="../assets/videoaulas.svg"/>
                </div>
            </div>
            <span class="span-title">Videoaulas</span>
        </div>
        <div style="margin-left:100px;">
            <div class="div-icons">
                <div class="library-icons">
                    <img src="../assets/materiais.svg"/>
                </div>
            </div>
            <span class="span-title" style="margin-left:45px;">Materiais</span>
        </div>
                <div style="margin-left:200px;">
            <div class="div-icons">
                <div class="library-icons">
                    <img src="../assets/coletaneas.svg"/>
                </div>
            </div>
            <span class="span-title" style="margin-left:37px;">Coletâneas</span>
        </div>
        <div style="margin-left:300px;">
            <div class="div-icons">
                <div class="library-icons" style="margin-top:18px;margin-left:25px;">
                    <img src="../assets/folha_redacao.svg"/>
                </div>
            </div>
            <span class="span-title" style="margin-left:20px;">Folhas de Redação</span>
        </div>
        <div style="margin-left:400px;">
            <div class="div-icons">
                <div class="library-icons">
                    <img src="../assets/tutoriais.svg"/>
                </div>
            </div>
            <span class="span-title" style="margin-left:48px;">Tutoriais</span>
        </div>
    </div>
    <div class="lastP">
        <div class="news">
            <span class="span-news">Caminhos para a melhoria da segurança pública no Brasil<span class="span-span">ENEM</span></span>
            <span class="span-news">Caminhos para a melhoria da segurança pública no Brasil<span class="span-span">ENEM</span></span>
            <span class="span-news">Caminhos para a melhoria da segurança pública no Brasil<span class="span-span">ENEM</span></span>
            <span class="span-news">Caminhos para a melhoria da segurança pública no Brasil<span class="span-span">ENEM</span></span>
            <span class="span-news">Caminhos para a melhoria da segurança pública no Brasil<span class="span-span">ENEM</span></span>
        </div>
        <div>
            <span class="news-title">Últimas Propostas:</span>
            <a class="news-link">Acessar</a>
        </div>
    </div>
    <div class="upRed">
        <div class="upIcon">
            <img class="icon-r" src="../assets/surface1.svg"/>
        </div>
        <div>
            <span class="news-title">Subir Nova Redação</span>
            <a class="news-link">Faça o Upload</a>
        </div>
    </div>
    <div class="myRed">
        <div class="myIcon">
            <img class="icon-r" src="../assets/note.svg"/>
        </div>
        <div>
            <span class="news-title">Minhas Redações</span>
            <a class="news-link">Acessar</a>
        </div>
    </div>
    <div class="seeSimul">
        <div class="seeIcon">
            <img class="icon-r" src="../assets/simulados.svg"/>
        </div>
        <div>
            <span class="news-title">Visualizar Simulados</span>
            <a class="news-link">Acessar</a>
        </div>
    </div>
</div>
</template>
<style>
.icon-r{
    height: 90px;
    margin-top: 30px;
    margin-left: 55px;
}
.seeSimul{
    position: fixed;
    width: 320px;
    height: 250px;
    margin-top: 40px;
    margin-left: 745px;
    background: #f5fffa;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
}
.myRed{
    position: fixed;
    width: 320px;
    height: 250px;
    margin-top: 40px;
    margin-left: 388px;
    background: #f5fffa;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
}
.upRed{
    position: fixed;
    width: 310px;
    height: 250px;
    margin-top: 40px;
    margin-left: 40px;
    background: #f5fffa;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
}
.news-title{
    font-weight: bold;
    position: fixed;
    margin-top: 30px;
    margin-left: 25px;
}
.news-link{
    position: fixed;
    color:#7F63F4;
    margin-top: 55px;
    margin-left: 25px;
    font-size: .75rem;
}
.span-span{
    margin-left: 12px;
}
.span-news{
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    font-size: .85rem;
    margin-left: 20px;
    line-height: 28px;
    color: #FFF;
    display:block;
    width:100%;
    min-width:1px;
}
.span-title{
    position: fixed;
    margin-top: 160px;
    margin-left: 40px;
    font-size: .8rem;
}
.div-icons{
    position: fixed;
    width: 65px;
    height: 65px;
    transform: matrix(0.71, 0.71, -0.71, 0.71, 0, 0);
    background-color: #FFF;
    border-radius: 20px;
    margin-top: 85px;
    margin-left: 40px;
    transform: .5s;
}
.lastP{
    width: 435px;
    height: 250px;
    margin-top: -250px !important;
    margin-left: 630px;
    background: #FFFFFF 0% 0% no-repeat padding-box;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
}
.library-title{
    font-weight: bold;
    position: fixed;
    margin-top: 30px;
    margin-left: 40px;
}
.library-icons{
    position: fixed;
    margin-top: 20px;
    margin-left: 20px;
    transform: rotate(-45deg);
}
.library{
    width: 550px;
    height: 250px;
    margin-top: 40px;
    margin-left: 40px;
    background: #f5fffa;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
}
.dashMain{
    position: fixed;
    top: 0;
    width: 100%;
    height: 100%;
    margin-top: 80px;
    margin-left: 33.33vh;
    background-color: #FFFBEF;
}

/* Hover Effects */ 

.div-icons:hover{
    background-color: #0000000F;
    cursor: pointer;
}
.upIcon:hover{
    background-color: #FFF;
    opacity: .9;
}
.seeIcon:hover{
    background-color: #FFF;
    opacity: .9;
}
.myIcon:hover{
    background-color: #FFF;
    opacity: .9;
}

/* Gradient Colors - "Icons" */

.upIcon{
    height: 150px;
    background: linear-gradient(294deg, #D9000F, #EA5703, #EBAE1D);
    transform: .9s;
}
.seeIcon{
    height: 150px;
    background: linear-gradient(294deg, #FF8359, #FFDF40);
    transform: .9s;
}
.myIcon{
    height: 150px;
    background: linear-gradient(294deg, #F5317F, #FF7C6E);
    transform: .9s;
}
.news{
    background: linear-gradient(110deg, #7596F6, #69ABF5);
}
</style>