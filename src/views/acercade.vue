<template>
    <hr>
  <div>
    <h1>B.T</h1>
    <P>DESARROLLADOR</P>
  </div>
  <hr />
  <div class="cont-general">
    <div class="cont-1">
      <label for="">BREVE RESUMEN</label>
      <p>
        Párrafo. Haz clic para editar y agregar tu propio texto. Es fácil. Haz
        clic en "Editar texto" o doble clic aquí para agregar tu contenido y
        cambiar la fuente. Puedes arrastrar y soltar este texto donde quieras en
        tu página. En este espacio puedes contar tu historia y permitir a los
        usuarios saber más sobre ti. Este es un gran espacio para escribir un
        texto largo sobre tu empresa y servicios. Puedes usar este espacio para
        entrar en más de detalle sobre tu empresa. Habla de tu equipo y los
        servicios que ofreces. Cuenta a los visitantes la historia de cómo se te
        ocurrió la idea de tu negocio y qué te diferencia de tus competidores.
        Haz que tu empresa se destaque y muestra a los visitantes quién eres.
      </p>
    </div>
    <div class="cont-2">
      <img src="../assets/pagina1jpg.jpg" alt="" />
    </div>
  </div>
  <hr>
  <div class="cont-complemento">
    <div class="con">
        <h3>
            EDUCACION
        </h3>
        <P>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Autem, quos maiores aperiam numquam consequuntur eius hic quae dolor doloribus dignissimos corporis, totam esse. Magni sit odio, sed voluptate repellendus veniam.</P>
    </div>
    <div class="con1">
        <h3>
            COMPETENCIAS
        </h3>
        <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae ad natus voluptatum odit eaque temporibus recusandae, unde odio veniam quod voluptatem placeat quidem asperiores reprehenderit repellat exercitationem fugit, sapiente neque.</P>
    </div>
  </div>
  <hr>

</template>
<script>
export default {
  name: "acercade-vue",
};
</script>
<style scoped>
.con{
    width: 90%;
}
.cont-complemento{
    display: flex;
    margin-top: 40px;
    margin-bottom: 80px;
}
p {
  text-align: left;
  margin-left: 20px;
}
h1 {
  text-align: left;
  margin-left: 20px;
}
label {
  font-size: 30px;
  text-align: left;
  margin-left: 20px;
}

.cont-2 {
  width: 100%;
}
.cont-1 {
  width: 100%;
  text-align: left;
}
img {
  height: 40vh;
}
.cont-general {
  display: flex;
  margin-top: 40px;
}
* {
  font-family: "Lobster", cursive;
}
@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");
</style>
