<template>
    <div id="main-banner">
        <h1>Monte seus Pedidos</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
    
}
</script>

<style scoped>

#main-banner {
  background-image: url('/public/img/burguer.jpg');
  background-position: right bottom -200px;
  background-size: cover;
  height: 900px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 80px;
  padding: 50px 40px;
}
@media (max-width: 1061px) {
  #main-banner {
    background-position: right bottom;
  }
}
</style>