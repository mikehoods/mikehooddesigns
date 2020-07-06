<template>
  <div>
    <div class="img-container">
      <img src="images/dessertview.jpeg">
    </div>
    <h1>Austin based developer open to new opportunities.</h1>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>


<style scoped>
  .img-container {
    display: flex;
    justify-content: center;
  }
  img {
    width: 100vw;
    opacity: 50%;
    background-repeat: repeat-y;
  }
  h1 {
    position: absolute;
    top: 15%;
    font-family: 'Lato', sans-serif;
  }
</style>