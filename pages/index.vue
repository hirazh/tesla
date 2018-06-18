<template>
  <section class="hero homepage">
    <div class="container main-container">
      <p class="title page-title">Quickest Acceleration.<br> Longest Range. The Safest Cars Ever.</p>
      <div class="container tesla-model-wrapper">
        <div class="columns">
          <div class="column">
            <nuxt-link to="/modelS"><a><div class="tesla-models">MODEL S</div></a></nuxt-link>
          </div>
          <div class="column">
            <nuxt-link to="/modelX"><a><div class="tesla-models">MODEL X</div></a></nuxt-link>
          </div>
          <div class="column">
            <nuxt-link to="/model3"><a><div class="tesla-models">MODEL 3</div></a></nuxt-link>
          </div>
          <div class="column">
            <nuxt-link to="/roadster"><a><div class="tesla-models">ROADSTER</div></a></nuxt-link>
          </div>
        </div>
      </div>
      <p class="news">GET NEWSLETTER ></p>
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
  background-image: url('../assets/images/homepage.jpg');
  background-size: cover;
  background-position-y: center;
  height: 90vh;
}

.page-title{
    font-size: 2.5rem;
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
  font-size: 1rem;
  font-weight: 500;
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
  font-size: 14px;
}

@media only screen and (max-width: 1100px){
  .page-title{
    font-size: 2rem;
  }

  .tesla-models {
    width: 130px;
  }

  .footer-part a {
    font-size: 12px;
    margin-left: 10px;
    margin-right: 10px;
    text-align: center;
  }
}

@media only screen and (max-width: 750px){
  .homepage {
    
  }

  .page-title{
    font-size: 1.5rem;
    margin-top: 15%;
  }

  .tesla-model-wrapper {
    display: flex;
    flex-flow: row wrap;
  }
  .footer-part a {
    font-size: 10px;
  }

  .tesla-models {
    width: 100px;
    font-size: 0.8rem;
  }

  .footer-part {
    visibility: hidden;
  }

  .news {
    padding-top: 15%;
  }

  @media only screen and (max-width: 750px){
    .page-title{
      font-size: 1.2rem;
      margin-top: 10%;
    }

    .news {
      font-size: 0.8rem;
    }

  }
}
</style>
