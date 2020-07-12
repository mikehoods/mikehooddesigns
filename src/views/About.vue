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
        <img class="me" src="images/lookatme.png">
        <div class="links">
          <a href="https://www.linkedin.com/in/michaelhoods/" target="_blank"><img src="images/LI.png"></a>
          <a href="https://github.com/mikehoods" target="_blank"> <img src="images/github.png"></a>
          <a href="https://medium.com/@michaelhoods" target="_blank"> <img src="images/Monogram.png"></a>
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
  .me {
    max-width: 8vw;
    border-radius: 50%;
    border: 2px solid whitesmoke;
    position: absolute;
    left: 6%;
    top: 8%;
  }
  .links {
    display: flex;
    justify-content: center;
    align-items: center;
    img {
      width: 3vw;
    }
    a {
      padding: .4rem;
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
    top: 9%;
    left: 20%
  }
  ul {
    font-size: 1.6rem;
    top: 30%;
    left: 62%;
    font-weight: 300;
    li {
      list-style: inside;
      font-size: 1.4rem;
      padding: 0 0 0 2rem;
    }
  }
}
@media only screen and (max-width: 800px) {
  .card {
    .links {
      img {
        width: 6vw;
      }
    }
    .me {
      max-width: 12vw;
      left: 2%;
    }
    h1 {
      font-size: 1.5rem;
      top: -6%
    }
    ul {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      left: 2%;
      font-size: 1.1rem;
      li {
        list-style: none;
        font-size: 1.1rem;
      }
    }
  }
}
</style>