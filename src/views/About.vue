<template>
  <div>
    <div class="card hoverable">
      <div class="img-container">
        <img src="images/scenicdessert.png">
      </div>
      <div class="card-content">
        <h1 class="card-title">Austin based developer open to new opportunities.</h1>
        <div class="links">
          <a href="https://www.linkedin.com/in/michaelhoods/"><img src="images/LI.png"></a>
          <a href="https://github.com/mikehoods"> <img src="images/github.png"></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>


<style lang="scss" scoped>
.card {
  border-radius: 12px;
  .img-container {
    display: flex;
    justify-content: center;
    img {
    width: 100%;
    // opacity: 50%;
    border-radius: 12px 12px 0 0;
  }
  }
  .links {
    display: flex;
    justify-content: center;
    align-items: center;
    img {
      width: 3vw;
    }
  }
  h1 {
    position: absolute;
    top: 25%;
    font-family: 'Lato', sans-serif;
    font-size: 2rem;
  }
}
@media only screen and (max-width: 600px) {
  .card {
    .links {
      img {
        width: 6vw;
      }
    }
    h1 {
      font-size: 1.5rem;
    }
  }
}
</style>