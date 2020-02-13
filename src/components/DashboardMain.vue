<template>
<div>
    <div class="div-dashMain">
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
    </div>
        <div class="div-dashMobile">
            <div class="dashMobile">
                <nav class="navbar" role="navigation" aria-label="main navigation">
                    <div class="navbar-brand">
                        <a class="navbar-item">
                            <img src="../assets/logo-home-small.png" class="icon-nav-mobile">
                        </a>

                        <a onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');" role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                            <span aria-hidden="true"></span>
                            <span aria-hidden="true"></span>
                            <span aria-hidden="true"></span>
                        </a>
                    </div>
                </nav>
                <div class="navbar-menu">
                    <aside class="menu">
                        <ul class="menu-list">
                            <li>
                                <a>
                                    <img src="../assets/home-disable.svg" />
                                    Painel
                                </a>
                                <a>
                                    <img src="../assets/file.svg" />
                                    Minhas Redações
                                </a>
                                <a>
                                    <img src="../assets/propostas.svg" />
                                    Propostas
                                </a>
                                <a>
                                    <img src="../assets/simulado.svg" />
                                    Simulados
                                </a>
                            </li>
                            <p class="menu-label">
                                BIBLIOTECA
                            </p>
                            <li>
                                <a>
                                    <img src="../assets/videoaulas-1.svg" />
                                    Videoaulas
                                </a>
                                <a>
                                    <img src="../assets/tutoriais-1.svg" />
                                    Tutoriais
                                </a>
                                <a>
                                    <img src="../assets/materiais-1.svg" />
                                    Materiais
                                </a>
                                <a>
                                    <img src="../assets/folha_redacao-1.svg" />
                                    Folhas de Redação
                                </a>
                            </li>
                        </ul>
                    </aside>
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
</div>
</template>