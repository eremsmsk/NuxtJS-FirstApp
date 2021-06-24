<template>
  <div class="container">
    <h1>products Id page</h1>
    <h2> Products Id : {{ $route.params.productId }}</h2>
    <nuxt-link to="/products" tag="a" class="button--green">Geri</nuxt-link>
    <button class="button--green" @click="showEditPage">Düzenle</button>
  </div>
</template>
<script>
export default {
    validate(arg){
        console.log(arg);
        return /^\d+$/.test(arg.params.productId); //Regex kalıp
    },
  data() {
    return {
    //   productID = null,
    };
  },
  methods: {
      showEditPage() {
        this.$router.push("/products/" + this.$route.params.productId + "/edit");
      },
  }
};
</script>
<style>
</style>