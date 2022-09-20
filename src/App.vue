
<template>
  <header>
    <div class="card p-2 bg-transparent border-0 justify-content-center row">
      <h1 class="title-card">¡Bangtan pizzas!</h1>
      <div class="row justify-content-center">
        <a class="btn mt-3" href="https://www.dominos.com.mx/menu/pizzas" target="_blank">Pide tu pizza</a>
      </div>
    </div>
  </header>
  <main>

      <div class="card p-3 bg-transparent">
        <h1 class="card-title">Disfruta de increíbles paquetes</h1>
      </div>

      <div class="contenedor">
      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/PE/PE.png" 
      nombre ="PEPPERONI"
      detalles="Tu ingrediente favorito en una masa fresca y hecha a mano"
      Ingredientes="Pepperoni"
      precio="120.00"
      >
      </card>
  
      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/HNC/HNC.png" 
      nombre ="HAWAIANA"
      detalles="La pizza que unos cuestionan pero todos aman. Jamón, piña."
      Ingredientes="Jamón y Piña"
      precio="110.00"
      >
      </card>
  
      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/MEX/MEX.png" 
      nombre ="TEXAS BBQ"
      detalles="¡Ajúaa! Arre por esta pizza con salsa BBQ, queso mozzarella, tocino, pollo fresco y carne molida bien cocida, sabores que te harán amarla."
      Ingredientes="Carne molida, tocino, pollo, salsa BBQ"
      precio="150.00"
      >
      </card>
  
      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/CBBQ/CBBQ.png" 
      nombre ="CHEESY BBQ"
      detalles="Todo perfectamente horneado para un sabor irresistible…"
      Ingredientes="Jalapeño, queso mozzarella,provolone,queso cheddar, pollo y cebolla"
      precio="112.20"
      >
      </card>
  
  
      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/4Q/4Q.png" 
      nombre ="CUATRO QUESOS"
      detalles="La pizza pensada en los amantes del queso. Queso mozzarella, queso crema, queso cheddar, queso parmesano."
      Ingredientes="Queso Crema, Mozzarella, Parmesano y Cheddar"
      precio="80.00"
      >
      </card>
  
      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/PES/PES.png" 
      nombre ="PEPPERONI ESPECIAL"
      detalles="La combinación perfecta entre Pepperoni y Champiñones, con un gran sabor y horneado al momento."
      Ingredientes="Pepperoni, Champiñones Frescos y Extra Queso"
      precio="112.20"
      >
      </card>
  
      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/CF/CF.png" 
      nombre ="CARNES FRÍAS"
      detalles="La pizza para los amantes de la carne. Salami, pepperoni, jamón, finas hierbas."
      Ingredientes="Pepperoni, Salami, Jamón y Finas Hierbas"
      precio="122.00"
      >
      </card>

      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/TEXAS/TEXAS.png" 
      nombre ="CHICKEN HAWAIANA"
      detalles="La pizza más tropical que tenemos. Pollo, tocino, piña, salsa mango habanero."
      Ingredientes="Pollo, Tocino, Piña y Salsa de Mango Habanero"
      precio="111.00"
      >
      </card>
    </div>
  </main>
<!-- Footer -->
<footer class="page-footer font-small pt-5">

  <div class="text-center text-md-left">
    <div class="row">
      <div class="col-md-6 mt-md-0 mt-3">
        <a href="https://www.dominos.com.mx/tiendas">Nuestras sucursales</a><br>
        <a href="https://www.dominos.com.mx/facturacion">Facturación Electrónica</a><br>
        <a href="https://www.dominos.com.mx/terminos-y-condiciones">Términos y condiciones</a><br>

      </div>


  
      <div class="col-md-6 mb-md-0 mb-3">

    
        <a href="https://www.dominos.com.mx/politicas-de-privacidad">Aviso de privacidad</a><br>
        <a href="http://responsabilidad.dominos.com.mx/viviendoenequilibrio/alime">Viviendo en Equilibrio</a><br>
        <a href="https://www.dominos.com.mx/quienes-somos">¿Quienes somos?</a><br>
        
      </div>


    </div>


  </div>
  <div class="footer-copyright text-center py-4">© 2022 Copyright:
    <a href="/"> Pizzeria</a>
  </div>

</footer>

</template>
<script>
  import Card from "./components/Card.vue"
  
  export default{
    components:{
      Card
    },
  };
</script>
<style scoped>
  *{
    margin: 0;
  }
  a{
    text-decoration: none;
  }
header{
  background-image: url(https://www.garciadepou.com/blog/wp-content/uploads/2016/08/pizza.jpg);
  height: 60vh;
  background-repeat: no-repeat;
  background-size:cover;
}
header h1{
  color: red;
  font-size: 50px;
  font-weight: 800;
  font-family: 'Oswald', sans-serif;
  margin-top: 150px;
  text-align: center;
  backdrop-filter: blur(2px);
}

@font-face {
  font-family: 'Oswald', sans-serif;
  src: url('https://fonts.googleapis.com/css2?family=Oswald:wght@600&display=swap');
}
.btn{
  color:white;
  border:solid red .1rem;
  width: 150px;
  backdrop-filter: blur(5px);
  font-weight: 600;
}
.contenedor{
  width: 90%;
}
@media screen and (max-width: 380px){
    header h1{
      font-size: 30px;
      margin-top: 50px;
    }
    .btn{
      width:100px;
      font-weight: 300;
    }
  }
  footer{
    background-image: linear-gradient(rgb(228, 121, 155),rgb(211, 90, 128),rgb(150, 43, 77));
    height: 30vh;
  }
  footer a{
    color: white;
  }
</style>


