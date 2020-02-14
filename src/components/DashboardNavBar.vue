<template>
    <nav class="navbar is-transparent dashMainNav">
        <div class="navbar-menu">
            <div class="navbar-end">
                <div class="navbar-item has-dropdown is-hoverable">
                    <img src="../assets/profile.svg" class="profile-img"/>
                    <a class="navbar-link">
                        Gerald Smith
                    </a>
                    <div class="navbar-dropdown is-right is-boxed">
                        <a class="navbar-item">
                            Meu Perfil
                        </a>
                        <router-link to="/">
                            <a class="navbar-item">
                                Sair
                            </a>
                        </router-link>
                    </div>
                </div>
                <a class="button is-white notification-btn">
                    <img src="../assets/notification.svg" class="notification-img"/>
                </a>
            </div>
        </div>
    </nav>
</template>