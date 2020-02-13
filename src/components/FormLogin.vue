<template>
    <div class="background">
      <div class="gradient-color-overlay"></div>
      <div class="formLogin">
        <img src="../assets/logo-home-small.png"/>
        <br>
        <span>Acesse Sua Conta</span>
        <section class="fields-custom">
          <b-field label="*Email">
            <b-input type="email">
            </b-input>
          </b-field>
          <b-field label="*Password">
            <b-input type="password" password-reveal>
            </b-input>
          </b-field>
          <div class="field">
            <b-checkbox class="label-checkbox">Lembrar de mim</b-checkbox>
            <a class="label-end">Esqueceu sua senha?</a>
          </div>
        </section>
        <router-link to="/dashboard"><b-button class="btn-login">Fazer Login</b-button></router-link>
      </div>
      <div class="formLoginMobile">
        <img class="logo-mobile" src="../assets/logo-dash-small.png"/>
        <br>
        <span>Acesse Sua Conta</span>
        <section class="fields-custom">
            <b-input type="email" placeholder="E-mail"></b-input>
            <b-input type="password" placeholder="Senha">
            </b-input>
        </section>
        <div class="field">
          <a class="label-end">Esqueceu sua senha?</a>
        </div>
        <router-link to="/dashboard"><b-button class="btn-login">Fazer Login</b-button></router-link>
      </div>
    </div>
</template>