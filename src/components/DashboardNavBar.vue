<template>
<div class="dashNav">
    <section>
        <b-dropdown class="sect-drop" hoverable aria-role="list">
            <button class="button" slot="trigger">
                <div class="profile-img">
                    <img class="profile-img" src="../assets/profile.svg"/>
                </div>
                <span class="profile-name">Gerald Smith</span>
                <span class="profile-type">ALUNO</span>
            </button>

            <img class="img-drop" src="../assets/profile.svg"/>
            <b-dropdown-item class="itens-drop" aria-role="listitem">Meu Perfil</b-dropdown-item>
            <img class="img-drop" src="../assets/logout.svg"/>
            <router-link to="/"><b-dropdown-item class="itens-drop" aria-role="listitem">Sair</b-dropdown-item></router-link>
        </b-dropdown>
        <span class="span-esp">&nabla;</span>
        <div class="div-notif">
            <button class="btn-notif">
                <img class="img-notif" src="../assets/notification.svg"/>
            </button>
        </div>
    </section>
</div>
</template>
<style>
    .span-esp{
        color:#979797;
        position: fixed;
        margin-top: 10px;
    }
    .sect-drop{
        margin-left: 110vh;
    }
    .div-notif{
        margin-top: -50px !important;
        margin-left: 137vh;
    }
    .btn-notif{
        background-color: #fff;
        border-radius: 0 !important;
        border: none !important;
        transition: .5s;
        width: 50px;
    }
    .img-notif{
        width: 24px;
        height: 50px;
    }
    .btn-notif:hover{
        background-color: #F7F7F7;
    }
    .button{
        width: 160px;
        height: 45px !important;
        border-radius: 0 !important;
        border: none !important;
        transition: .5s;
    }
    .button:hover{
        background-color: #F7F7F7;
    }
    .profile-img{
        position: relative;
        margin-left: -60px;
        width:24px;
        height:24px;
    }
    .profile-name{
        text-align: left;
        font-size: .8rem;
        margin-top: -8px;
        margin-left: -20px;
        letter-spacing: 0.18px;
        color: #000;
        opacity: 1;
    }
    .profile-type{
        margin-top: 15px;
        margin-left: -76px;
        font-size: .5rem;
        letter-spacing: 0.18px;
        color: #979797;
        opacity: 1;
    }
    .img-drop{
        position: absolute;
        margin-left: 11px;
        margin-top: 9px;
        width: 16px;
        height: 16px;
    }
    .itens-drop{
        margin-left: 40px;
        width: 140px !important;
    }
    .dashNav {
        position: fixed;
        top: 0;
        width: 100%;
        height: 50px;
        margin-left: 33.33vh;
        box-shadow: 0px 2px 5px 0px #00000026;
    }
</style>