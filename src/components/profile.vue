<template>
      <div class="pagina1">
    <div class="cont-pagina1">
      <h1>01</h1>
    </div>
    <div class="cont-pagina2">
      <img class="img-pagina2" src="../assets/pagina1jpg.jpg" alt="" >
      <div class="estado-cont">
        <h3>sin conocimientps</h3>
      <h4>definir</h4>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti neque mollitia <br>
         perferendis quas, excepturi veniam dolore ratione quibusdam voluptatem, accusamus <br>
          fugiat, dignissimos tenetur quia officia nobis laborum. Veritatis, accusamus earum.</p>
          <input type="button" value="Ver perfil"   >
      
      </div>
      
    </div>
  </div>
</template>
<script>
export default{
    name:'profile-vue'
}
</script>
<style scoped>

.estado-cont{
  text-align: left;
}
.img-pagina2{
  width: 24%;
}
.cont-pagina2{
width: 80%;

}
.cont-pagina1{
width: 20%;
padding-left: 20px;
text-align:left ;
}
.pagina1{
  margin-top: 40px;
  display: flex;
  height: 70vh;
}
input{
    border: 1px solid green;
    background-color: transparent;
    padding: 10px 50px 10px 50px;
    border-radius: 20px;
    margin-top: 30px;
    margin-bottom: 20px;
}

</style>