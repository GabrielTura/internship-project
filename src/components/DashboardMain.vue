<template>
<div>
    <div class="div-dashMain">
        <div class="dashMain">
            <div class="columns">
                <div class="column is-two-thirds">
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
                </div>
                <div class="column is-half">
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
                </div>
            </div>
            <div class="upRed">
                <div class="upIcon">
                    <img class="icon-r" src="../assets/surface1.svg"/>
                    <img class="balls" src="../assets/balls.png"/>
                </div>
                <div>
                    <span class="news-title">Subir Nova Redação</span>
                    <a class="news-link">Faça o Upload</a>
                </div>
            </div>
            <div class="myRed">
                <div class="myIcon">
                    <img class="icon-r" src="../assets/note.svg"/>
                    <img class="balls" src="../assets/balls.png"/>
                </div>
                <div>
                    <span class="news-title">Minhas Redações</span>
                    <a class="news-link">Acessar</a>
                </div>
            </div>
            <div class="seeSimul">
                <div class="seeIcon">
                    <img class="icon-r" src="../assets/simulados.svg"/>
                    <img class="balls" src="../assets/balls.png"/>
                </div>
                <div>
                    <span class="news-title">Visualizar Simulados</span>
                    <a class="news-link">Acessar</a>
                </div>
            </div>
        </div>
    </div>
        <div class="div-dashMobile">
            <div class="dashMobile">
                <nav class="navbar" role="navigation" aria-label="main navigation">
                    <div class="navbar-brand">
                        <a class="navbar-item">
                            <img src="../assets/logo-home-small.png" class="icon-nav-mobile">
                        </a>

                        <a role="button" onclick="document.getElementById('nav-active').classList.toggle('is-active');" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                            <span aria-hidden="true"></span>
                            <span aria-hidden="true"></span>
                            <span aria-hidden="true"></span>
                        </a>
                    </div>
                </nav>
                <div class="navbar-menu" id="nav-active">
                    <aside class="menu">
                    <ul class="menu-list">
                        <li>
                            <a class="menu-li-active">
                                <img src="../assets/home.svg" style="position: absolute;"/>
                                <span class="menu-li-text-active">Painel</span>
                            </a>
                            <a>
                                <img src="../assets/file.svg" class="menu-li-img"/>
                                <span class="menu-li-text">Minhas Redações</span>
                            </a>
                            <a>
                                <img src="../assets/propostas.svg" class="menu-li-img"/>
                                <span class="menu-li-text">Propostas</span>
                            </a>
                            <a>
                                <img src="../assets/simulado.svg" class="menu-li-img"/>
                                <span class="menu-li-text">Simulados</span>
                            </a>
                            <hr>
                            <a>
                                <img src="../assets/videoaulas-1.svg" class="menu-li-img"/>
                                <span class="menu-li-text">Videoaulas</span>
                            </a>
                            <a>
                                <img src="../assets/tutoriais-1.svg" class="menu-li-img"/>
                                <span class="menu-li-text">Tutoriais</span>
                            </a>
                            <a>
                                <img src="../assets/materiais-1.svg" class="menu-li-img"/>
                                <span class="menu-li-text">Materiais</span>
                            </a>
                            <a>
                                <img src="../assets/folha_redacao-1.svg" class="menu-li-img"/>
                                <span class="menu-li-text">Folhas de Redação</span>
                            </a>
                            <router-link class="profile-menu" to="/">
                                <a>
                                    <img src="../assets/profile.svg" class="profile-img-menu" />
                                    <span class="profile-name-menu">Gerald Smith</span>
                                    <div class="profile-type-menu"><span>ALUNO</span></div>
                                    <img src="../assets/logout.svg" class="profile-img-menu profile-img-exit" />
                                </a>
                            </router-link>
                        </li>
                    </ul>
                    </aside>
                </div>
            </div>
                <div class="card-item">
                    <div class="card-i-align">
                        <img class="card-i-align-img" src="../assets/file-w.svg" />
                        <span class="card-i-align-text">Minhas Redações</span>
                    </div>
                </div>
                <div class="card-item card-item-p">
                    <div class="card-i-align">
                        <img class="card-i-align-img" src="../assets/propostas-w.svg" />
                        <span class="card-i-align-text">Propostas</span>
                    </div>
                </div>
                <div class="card-item card-item-s">
                    <div class="card-i-align">
                        <img class="card-i-align-img" src="../assets/simulados-w.svg" />
                        <span class="card-i-align-text">Simulados</span>
                    </div>
                </div>
                <br>
                <span class="span-div-carousel">Biblioteca</span>
                <div class="div-carousel">
                    <carousel>
                        <slide class="carousel-slides">
                            <div class="carousel-item">
                                <div>
                                    <img src="../assets/videoaulas.svg" />
                                </div>
                                <span>Videoaulas</span>
                            </div>
                        </slide>
                        <slide class="carousel-slides">
                            <div class="carousel-item">
                                <div>
                                    <img src="../assets/tutoriais.svg" />
                                </div>
                                <span>Tutoriais</span>
                            </div>
                        </slide>
                        <slide class="carousel-slides">
                            <div class="carousel-item">
                                <div>
                                    <img src="../assets/materiais.svg" />
                                </div>
                                <span>Materiais</span>
                            </div>
                        </slide>
                        <slide class="carousel-slides">
                            <div class="carousel-item">
                                <div>
                                    <img src="../assets/folha_redacao.svg" />
                                </div>
                                <span>Folhas de Redação</span>
                            </div>
                        </slide>
                    </carousel>
                </div>
                <div class="tabs is-centered">
                    <ul>
                        <li>
                            <a>
                                <span class="icon is-small"><img src="../assets/profile.svg" /></span>
                            </a>
                        </li>
                        <li>
                            <a>
                                <span class="icon is-small"><img src="../assets/file.svg" /></span>
                            </a>
                        </li>
                        <li class="is-active">
                            <a>
                                <span class="icon is-small"><img src="../assets/home.svg" /></span>
                            </a>
                        </li>
                        <li>
                            <a>
                                <span class="icon is-small"><img src="../assets/notification.svg" /></span>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
</template>