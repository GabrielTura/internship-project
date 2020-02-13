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