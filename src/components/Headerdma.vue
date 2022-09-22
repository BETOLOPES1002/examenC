<template>
    <header>
    <h1>¡Bangtan pizzas!</h1>
    <button onclick="window.open('https://www.dominos.com.mx/menu/pizzas')">Ordenar</button>
</header>
</template>
<script>

</script>

<style>
   @font-face {
  font-family: 'Oswald', sans-serif;
  src: url('https://fonts.googleapis.com/css2?family=Oswald:wght@600&display=swap');
}
header{
    background-image: url("https://www.garciadepou.com/blog/wp-content/uploads/2016/08/pizza.jpg");
    height: 60vh;
    background-repeat: no-repeat;
    background-size:cover;
    text-align: center;
}
header h1{
  color: red;
  font-size: 50px;
  font-weight: 800;
  font-family: 'Oswald', sans-serif;
  padding-top: 25vh;
  text-align: center;
  backdrop-filter: blur(2px);
}
button{
    text-decoration: none;
    padding: 10px;
    border: solid white 1px;
    background:transparent;
    color:white;
  border:solid red .1rem;
  width: 150px;
  backdrop-filter: blur(3px);
  font-weight: 600;
  font-size: 1rem;
}
</style>