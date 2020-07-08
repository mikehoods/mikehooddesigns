<template>
  <div>
    <div class="card hoverable">
      <div class="img-container">
        <img src="images/scenicdessert.png">
      </div>
      <div class="card-content">
        <h1 class="card-title">Austin based fullstack developer open to new opportunities.</h1>
        <ul>Primary Skillset:
            <li>Javascript</li>
            <li>Python</li>
            <li>Vue</li>
            <li>Express</li>
            <li>React</li>
            <li>MongoDB</li>
        </ul>
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
  margin-top: 10vh;
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
  h1, ul{
    position: absolute;
    font-family: 'Lato', sans-serif;
    color: whitesmoke;
    text-shadow: .5px .5px black;
  }
  h1 {
    font-size: 2.1rem;
    top: 10%;
  }
  ul {
    font-size: 1.4rem;
    top: 35%;
    left: 10%;
    li {
      list-style: inside;
      font-size: 1.2rem;
      padding: 0 0 0 2rem;
    }
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