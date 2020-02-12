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
<style>
@media only screen and (max-width: 600px) {
  .tt{
    display: none;
  }
  .logo-mobile{
    margin-top: -50px;
    margin-bottom: 80px;
  }
  .formLogin {
    display: none;
  }
  .footer-home{
    display: none;
  }
  .fields-custom{
    line-height: 45px;
  }
  .label-end{
    margin-left: 55px !important;
    color: #fff !important;
    text-decoration-line: underline;
    font-weight: 200;
  }
  .label-end:hover{
    color: #fff !important;
  }
  .btn-login{
    background-color: #D7311C !important;
    width: 210px !important;
  }
  .btn-login:hover{
    background-color: red !important;
  }
  ::placeholder {
    opacity: 1;
    font-size: 0.9rem;
    font-weight: 500;
  }
  .gradient-color-overlay {
    background: linear-gradient(226deg, #D9000FCC, #EA5703CC, #EBAE1DCC) !important;
    opacity: 1;
  }
  .background{
    background-size: cover !important;
    background-position-x: -400px !important;
  }
  .formLoginMobile {
    background-color:transparent;
    width: 330px;
    height: 450px;
    position: absolute;
    color: #fff;
    font-weight: bold;
    font-size: 17px;
    padding-left: 60px;
    padding-right: 60px;
  }
}
@media only screen and (min-width: 600px) {
  .formLogin{
    display: block;
  }
  .tt{
    display: none;
  }
  .btn-login{
    background-color: #EBAE1D !important;
  }
  .formLoginMobile{
    display: none;
  }
} 

.label {
  color: #A5220C !important;
}
.label-checkbox {
  color: #979797 !important;
  font-size: .9rem;
}
.label-end {
  color: #979797;
  font-size: .9rem;
  margin-left: 157px;
}
.label-end:hover {
  color: #707070;
}
.formLogin {
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
.fields-custom {
  margin-top: 20px;
  text-align: left;
}
.btn-login {
  margin-top: 25px;
  background-color: #EBAE1D;
  color: #FFF !important;
  width: 250px;
}
.gradient-color-overlay {
  width: 100%;
  height: 100%;
  background: linear-gradient(45deg, rgb(235, 174, 29), rgb(234, 87, 3), rgb(217, 0, 15));
  opacity: 0.7;
}
.background {
  background: #000 url("../assets/background-home.png");
  color: #fff;
  height: 600px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-size: cover !important;
}
</style>