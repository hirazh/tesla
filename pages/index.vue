<template>
  <section class="hero homepage">
    <div class="container main-container">
      <p class="title is-size-1">Quickest Acceleration.<br> Longest Range. The Safest Cars Ever.</p>
      <div class="container tesla-model-wrapper">
        <div class="columns">
          <div class="column">
            <a href="#"><div class="tesla-models">MODEL S</div></a>
          </div>
          <div class="column">
            <a href="#"><div class="tesla-models">MODEL X</div></a>
          </div>
          <div class="column">
            <a href="#"><div class="tesla-models">MODEL 3</div></a>
          </div>
          <div class="column">
            <a href="#"><div class="tesla-models">ROADSTER</div></a>
          </div>
        </div>
      </div>
      <p class="title is-size-6 news">GET NEWSLETTER ></p>
    </div>

    <div class="container footer-part">
      <a href="#">Tesla © 2018</a>|
      <a href="#">Privacy & Legal</a>|
      <a href="#">Contact</a>|
      <a href="#">Careers</a>|
      <a href="#">Get Newsletter</a>|
      <a href="#">Forums</a>|
      <a href="#">Locations</a>|
      <a href="#"><img src="../assets/images/usa-flag.png"></a>
    </div>
  </section>
</template>

<script>
export default {
  components: {
    
  }
}
</script>

<style>
.homepage {
  background-image: url('../assets/images/tesla-model-3.jpg');
  background-size: cover;
  height: 90vh;
}

.is-size-1 {
  color: #ffffff;
  padding: 4%;
  font-weight: 100;
  line-height: 150%;
}

.main-container {
  text-align: center;
}

.tesla-model-wrapper {
  display: flex;
  justify-content: space-around;
}

.tesla-models {
  background-color: black;
  opacity: 0.7;
  color: #ffffff;
  width: 180px;
  padding: 3%;
  
}

.news {
  color: #ffffff;
  padding: 5%;
}

.footer-part {
  color: #ffffff;
  display: flex;
  justify-content: center;
  margin-bottom: 3%;
}

.footer-part a {
  text-decoration: none;
  color: #f0f0f0;
  padding: 0 1% 0 1%;
  
}

</style>
