<template>
 <div> 
  <h1> Aporte su tema de discusión </h1>
  <form name="form" id="form">
    <p> Titulo: <input type="text" name="titulo" placeholder="Título" class="form-control"/> </p>
    <p> Email: <input type="text" name="correo" placeholder="Email" class="form-control"/> </p>
    <p> Nombre: <input type="text" name="nombre" placeholder="Nombre" class="form-control"/> </p>
    <p> Mensaje: <textarea name="mensaje" id="mensaje" cols="10" rows="10" placeholder="Mensaje" class="form-control"></textarea>
    </p>
    <hr />
    <input type="submit" value="Enviar" title="Enviar" class="btn btn-priimary" />
  </form>
 </div>


</template>


<script>
export default {
  name: 'HelloWorld',
  props: {
  
  }
}
</script>