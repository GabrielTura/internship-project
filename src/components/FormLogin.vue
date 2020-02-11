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
    </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.label{
  color: #A5220C !important;
}
.label-checkbox{
  color: #979797 !important;
  font-size: .9rem;
}
.label-end{
  color: #979797 !important;
  font-size: .9rem;
  margin-left: 157px;
}
.label-end:hover{
  color: #707070 !important;
}
.formLogin{
  background-color:#FFF;
  border-radius: 20px;
  width: 550px;
  height: 450px;
  position: absolute;
  color: #D9000F;
  font-size: 17px;
  padding-left: 60px;
  padding-right: 60px;
}
.fields-custom{
  margin-top: 20px;
  text-align: left;
}
.btn-login{
  margin-top: 25px;
  background-color: #EBAE1D !important;
  color: #FFF !important;
  width: 250px;
}
.gradient-color-overlay{
  width: 100%;
  height: 100%;
  background: linear-gradient(45deg, rgb(235, 174, 29), rgb(234, 87, 3), rgb(217, 0, 15));
  opacity: .7;
}
.background{
  background: #000 url("../assets/background-home.png");
  color: #fff;
  height: 600px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>