<template>
  <div class="hero">
    <img src="https://jonathanchoi.cdn.imgeng.in/assets/logo.png"/>
    <h1>My name is Jonathan Choi</h1>
  </div>
</template>

<script>
export default {
  name: "Hero",
  props: {
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  img {
    margin: auto;
  }
  h1 {
    color: white;
    padding-top: 1rem;
    text-align: center;
    margin: auto;
  }

  .hero{
    width: 100%;
    background-image: linear-gradient(to right, rgb(242, 112, 156), rgb(255, 148, 114));
    margin-bottom: 2rem;
    /* display: flex;
    align-items: center; */
    text-align: center;
    padding-top: 5rem;
    padding-bottom: 5rem;
  }
</style>
