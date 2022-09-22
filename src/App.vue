

<template>
    <headerdma>

    </headerdma>
<body>
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
  <footerdma>

  </footerdma>
</body>
 
</template>

<style scoped>

</style>


<script>
  import Card from "./components/Card.vue"
  import Footerdma from "./components/footerdma.vue"
import Headerdma from "./components/Headerdma.vue"

  export default {
    components:{ Card,Footerdma, Headerdma },
  };
</script>