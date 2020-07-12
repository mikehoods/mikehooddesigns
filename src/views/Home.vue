<template>
  <div class="body">
    <div class="projects">
    <div class="row">
    <div class="col m8 offset-m2 s12">
      <div class="card hoverable">
        <div class="card-image">
          <img src="images/dd_homevue.png">
          <a href="https://deardiary.netlify.app/" target="_blank" class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">link</i></a>
        </div>
        <div class="title-div">
          <span class="card-title">Dear Diary</span>
          <span class="techUsed card-title">Vue/Express/MongoDB/Auth0</span>
        </div>
        <div class="card-content">
          <p class="projectDesc">Easy to use online journal app created with Vue and Express. Log in through your Google account with Auth0.</p>
        </div>
      </div>
    </div>
  </div><div class="row">
    <div class="col m8 offset-m2 s12">
      <div class="card hoverable">
        <div class="card-image">
          <img src="images/h4m_cuisines.png">
          <a href="https://hungry4more.netlify.app/" target="_blank" class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">link</i></a>
        </div>
        <div class="title-div">
          <span class="card-title">Hungry 4 More</span>
          <span class="techUsed card-title">React/Express/MongoDB</span>
          
        </div>
        <div class="card-content">
          <p class="projectDesc">Find local restaurants by cuisine type. Login in to manage your favorite restaurants list.</p>
        </div>
      </div>
    </div>
  </div>
    <div class="row">
    <div class="col m8 offset-m2 s12">
      <div class="card hoverable">
        <div class="card-image">
          <img src="images/vic_indexnav.png">
          <a href="https://mikehood-ga-projects.herokuapp.com/plants" target="_blank" class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">link</i></a>
        </div>
        <div class="title-div">
          <span class="card-title">Victory</span>
          <span class="techUsed card-title">Express/MongoDB</span>
        </div>
        <div class="card-content">
          <p class="projectDesc">Swap plants, seeds, produce, and more with ease. View available items by type, or login in to manage your swaps, messages, and personal plant inventory.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="row">
    <div class="col m8 offset-m2 s12">
      <div class="card hoverable">
        <div class="card-image">
          <img src="images/nh_gameplay.png">
          <a href="http://mikehoods.github.io/notHangman" target="_blank" class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">link</i></a>
        </div>
        <div class="title-div">
          <span class="card-title">notHangman</span> <span class="techUsed card-title">Javascript</span>
        </div>
        <div class="card-content">
          
          <p class="projectDesc">Two player version of the classic game. Tracks scores for correct and incorrect guesses, and determines winner after two rounds.</p>
        </div>
      </div>
    </div>
  </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>
 

<style scoped>
.img-container {
    display: flex;
    justify-content: center;
    opacity: 25%;
  }
.img-container img {
  width: 100vw;
}
.projects {
  position: absolute;
  top: 10%;
  left: 0%;
  z-index: 5;
}
.card {
  margin-top: 3rem;
  font-family: 'Lora', serif;
  border-radius: 12px;
}
.card img {
  border: .5px solid lightgray;
  border-radius: 12px 12px 0 0;
}
.card p {
  font-family: 'Lato', sans-serif;
}
.techUsed {
  text-align: center;
  font-style: italic;
  font-size: 1rem;
  padding-top: .4rem;

}
.projectDesc {
  font-size: 1.2rem;
}
.title-div {
  background: linear-gradient(to right bottom, rgb(4, 3, 3), rgb(125, 124, 124));
   color: whitesmoke;
   padding: .5rem;
   justify-content: space-between;
   display: flex;
   align-items: center;
}
.card-content {
  background: linear-gradient(to right bottom, rgb(255, 255, 255), rgb(176, 237, 214));
  border-radius: 0 0 12px 12px;
}
</style>
