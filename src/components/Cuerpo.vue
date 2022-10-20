<template>
    <div class="p-3 border border-top-1 border-bottom-0">
        <h1>Entrega de Comida china cerca de mí</h1>
        <p>Explora los negocios cercanos que ofrecen entregas de Comida china a domicilio.</p>
      </div>
    
      <div class="contenedor row border border-top-1">
      <card url="https://okdiario.com/img/2021/03/10/recetas-chinas-655x368.jpg" 
      nombre ="Bamboo Wok - Volcanes"
      Ingredientes="25 - 30"
      precio="20"
      ordenar="https://www.ubereats.com/mx/store/bamboo-wok-volcanes/sAbU3HRCUnauLWry2QRgaQ"
      >
      </card>
    
      <card url="https://i.ytimg.com/vi/w5jg4tzYFQI/maxresdefault.jpg" 
      nombre ="Panda Chen"
      Ingredientes="25 - 30 "
      precio="14"
      ordenar="https://www.ubereats.com/mx/store/panda-chen-comida-china/6innBdQbSoGnmWbRTapGMQ"
      >
      </card>
    
      <card url="data:image/jpeg;base64,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" 
      nombre ="El mercado"
      Ingredientes="30 - 40"
      precio="20" 
      ordenar="https://www.ubereats.com/mx/store/el-mercado-volcanes/oX2yRu1BQVm4CVwB3nc04g"
      >
      </card>
    
      <card url="https://s1.eestatic.com/2017/01/28/cocinillas/cocinillas_189495667_116287820_1278x847.jpg" 
      nombre ="shirushi-plaza-inn"
      Ingredientes="30 - 45"
      precio="14"
      ordenar="https://www.ubereats.com/mx/store/shirushi-plaza-inn/ygOcEwGlRtWOX7b7k0hhGQ"
      >
      </card>
    
    
      <card url="https://media-cdn.tripadvisor.com/media/photo-s/1a/78/5a/d9/restaurante-muchang.jpg" 
      nombre ="Akiba Stop Maid Cafe"
      Ingredientes="20 - 30 "
      precio="18"
      ordenar="https://www.ubereats.com/mx/store/akiba-stop-maid-cafe/bJ06iYU5SNOaVggJ8KGnzg"
      >
      </card>
    
      <card url="https://animalgourmet.com/wp-content/uploads/2017/01/dumplings2-e1513610872911.jpg" 
      nombre ="Makum-Asia"
      Ingredientes="25 - 40"
      precio="16"
      ordenar="https://www.ubereats.com/mx/store/makum-asia/DqFGZLbTT62Ih47-7nEQLQ"
      >
      </card>
    
      <card url="https://dam.cocinafacil.com.mx/wp-content/uploads/2019/06/palillos.chinos.jpg" 
      nombre ="Daykito"
      Ingredientes="20 - 35 "
      precio="16"
      ordenar="https://www.ubereats.com/mx/store/daykito/oHi75BlHQ9Wv3LYiZTCw0w"
      >
      </card>
    
      <card url="https://i.ytimg.com/vi/yb1RAAMQdFg/maxresdefault.jpg" 
      nombre ="Sushi Chiri House"
      Ingredientes="Pollo, Tocino, Piña y Salsa de Mango Habanero"
      precio="111.00"
      ordenar="https://www.ubereats.com/mx/store/sushi-chiri-house/ersr9GCKRO-8W_ZTRE36Xg"
      >
      </card>
    </div>
</template>
<script>
import Card from "./Card.vue";
export default{
components:{
    Card
}
}
</script>
<style scoped>
</style>
