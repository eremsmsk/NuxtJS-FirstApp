<template>
  <section class="container">
    <h1 class="title">Home Page</h1>
    <p class="subtitle">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum facere
      officiis consequatur aut quis minus quidem, minima nam voluptatibus,
      molestias quo nobis rem. Hic explicabo aspernatur dolores, modi commodi
      corporis. Lorem ipsum dolor sit amet consectetur adipisicing elit.
      Praesentium quibusdam, omnis consectetur quos distinctio rerum accusamus
      exercitationem unde dolore sint ut impedit dicta obcaecati cum sequi ab
      dolorum recusandae molestiae?
    </p>

    <div class="button-container">
      <a href="#" class="button--green">Products</a>
      <a href="#" class="button--green">Product</a>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  text-align: center;
  margin-top: 50px;
}

.button-container {
  margin-top: 50px;
  border: 1px solid #392;
  background-color: #f0f0f0;
  padding: 10px;
  box-shadow: 2px 3px 8px rgba(0, 0, 0, 0.1);
  display: flex;
  justify-content: center;
}

.button--green {
  margin-left: 5px;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 25px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
</style>
