<template>
        <div class="col col-3 p-1">
        <img :src="url" :alt="nombre">
        <h2 class="mt-1">{{ nombre }}</h2>
        <p>Tiempo: {{Ingredientes}}</p>
        <p class="text-info">Costo de envio: ${{precio}}.00 MXN</p>
        <a :href="ordenar" target="_blank" class="m-1">Ordenar</a>
        </div>
</template>
<script>
export default{
    props:{
        url:{
            String,
        },
        nombre:{
            String,
        },

        precio:{
            Number,
        },
        Ingredientes:{
            String,
        },
        ordenar:{
            String,
        }
    },
};
</script>
<style scoped>
div{
    box-shadow: 0px 0px 20px gray;
    text-align: center;
    width: 30vw;
    margin: 20px;
    box-sizing: border-box;
}
div:hover{
    transform: scale(0.89,1.07);
        transition: 1s;
}
div>img{
    width: 300px;
}
@media screen and (max-width:900px) {
    div>img{
        width: 20vw;
    }
}
@media screen and (max-width:1000px) {
    div>img{
        width: 25vw;
    }
}
</style>