<template>
 

  <hr>
  <div class="home">
    <div class="cont">
    </div>
    <label class="title" for="">Desarrolador fullstack</label>
    <h1>BRAYAN TUNUBALA</h1>
    <P>Soy un DESARROLLADOR fullstack con muchas habilidades de backend</P>


    <div class="ahora">
      <div class="image">
        <img class="system" src="../assets/ingenieria-de-sistemas.jpg" alt="">
        <div class="cont-title">
        <h3>MI PROYECTO</h3>
        <p>creacion de maquetado con vuejs</p>
      </div>  
      </div> 
     
      
    </div>

  </div>
  <section class="box">
   <div class="box-div">
    <label class="portafolio" for="">MI PORTAFOLIO</label>
   </div>
  </section>
  <hr>
  <div>
    <profile/>
  </div>

  <hr class="bajar">

  <div>
    <Education/>
  </div>
</template>

<script>
// @ is an alias to /src

import Education from '@/components/education.vue';
import Profile from '@/components/profile.vue'

export default {
  name: 'HomeView',
  components: {
    Profile,
    Education
}
}
</script>
<style scoped>
.bajar{
margin-top: 150px;
}

.home{
 height: 80vh;
 text-align: left;
 margin-left: 20px;
 background-image: url('../assets/Snapchat-103809712.jpg');
  background-repeat: no-repeat;
  background-size: auto;
  background-position: 50%;
}
.cont{
  display: flex;
}
.title{
display: flex;
  margin-top: 10%;

  font-size: 30px;
}
h1{
  font-size: 50px;
}
.box{
display: flex;
margin-top: 100px;

}
.box-div{
  display: flex
}
.portafolio{
  margin-left: 20px;
  font-size: 50px
}
*{
  font-family: 'Lobster', cursive;
  background-color:#3f51b5 indigo;
}
.image{
  display: flex;
  border-radius: 10px;
  margin-top: 100px;
  width:450px;
  height:150px;
}
.system{
  width: 250px;
  border-radius: 10px;
}
.cont-title{
  margin-left: 30px
}
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
@import url("https://fonts.googleapis.com/icon?family=Material+Icons");
</style>
