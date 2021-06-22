<template>
<div class="container">
    <h1> Edit page </h1>
    <h2> Products Id : {{ $route.params.productId }} </h2>
    <nuxt-link :to="'/products/' + $route.params.productId" tag="a" class="button--green">Geri</nuxt-link>
    </div>    
</template>
<script>

</script>
<style>

</style>