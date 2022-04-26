<template>
<Banner/>
<div class="main-container">
  <h1>Monte seu Pedido!</h1>
    <forms/>
</div>
</template>

<script>
import Forms from '../components/forms.vue'
import Banner from '../components/Banner.vue'
export default {
  name: "Home",
  components: { 
    Banner,
    Forms 
    
    },
  
}
</script>


