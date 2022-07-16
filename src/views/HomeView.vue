<template>
  <div class="main-container">
    <Banner />
    <h1>Monte o seu burger</h1>
    <form>
      <BurgerForm />
    </form>
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import BurgerForm from '@/components/BurgerForm.vue';
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    Banner,
    BurgerForm
}
}
</script>
