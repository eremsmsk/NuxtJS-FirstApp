<template>
  <div class="container">
    <h1>products page</h1>
    <div class="input-container">
      <input type="text" v-model="productID" class="form-control" />
      <button class="button--green" @click="showProduct">Show Product</button>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      productID: null,
    };
  },
  methods: {
    showProduct() {
      this.$router.push("/products/" + this.productID);
    },
  },
};
</script>
<style>
</style>