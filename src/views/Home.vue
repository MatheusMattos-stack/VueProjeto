<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu burguer:</h1>
    <BurgerForm />
  </div>
</template>

<script>
import Banner from "../components/Atomos/Banner.vue";
import BurgerForm from "../components/Organismos/BurgerForm.vue";


export default {
  name: "Home",
  components: {
    Banner,
    BurgerForm
  }
}
</script>
