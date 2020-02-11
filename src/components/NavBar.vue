<template>
<b-navbar class="tt">
        <template slot="brand">
        <img style="margin-left:30px;width:133px;height:85px;" src="../assets/logo-home-small-wordmark.png">
        </template>
        <template slot="end">
            <span class="span-test">Acessar Como:</span>
            <img class="avatar" src="../assets/admin.svg"/>
            <img class="avatar" src="../assets/diretor.svg"/>
            <img class="avatar" src="../assets/corretor.svg"/>
            <img class="avatar" src="../assets/aluno.svg"/>
        </template>
    </b-navbar>
</template>
<style>
.span-test{
    margin-top: 39px;
    margin-right: 18px;
    text-align: left;
    font-size: 0.7rem;
    letter-spacing: 0.18px;
    color: #B3AFB3;
    opacity: 1;
}
.avatar {
    margin: 27px 5px 27px 5px;
    padding: 0 5px 0 5px;
    border-radius: 100px;
    border: 2px solid #cfd8dc;
    transition: 0.3s;
}

.avatar:hover{
    background-color: #707070;
    cursor: pointer;
}

.tt{
    height: 94px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>