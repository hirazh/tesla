<template>
  <div class="main-div">
    <Nav></Nav>
    <nuxt/>
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'

export default {
  components: {
    Nav
  }
}
</script>

<style>
* {
  border: 0;
  margin: 0;
  padding: 0;
}
.main-div {
    background-color: #4f4f4f;
}

.modelpage-wrapper {
    background-size: cover;
    text-align: center;
    height: 90vh;
}

.title1, .title2 {
    color: #f0f0f0;
}

.title1{
    font-size: 1.5rem;
}

.title2{
    font-size: 3rem;
}

.heading-title {
    margin-top: 3%;
}
.heading-title h3 {
    font-weight: 100;
}
.paragraph-wrapper {
    margin-top: 15%;
    margin-bottom: 0;
}

.para {
    color: #f0f0f0;
}

.spec-columns {
    color: #f0f0f0;
    width: 60%;
    text-align: center;
    display: flex;
    justify-content: center;
}
.specs {
    margin-bottom: 3%;
    display: flex;
    justify-content: center;
}
.spec-detail {
    font-size: 2rem;
    font-weight: bolder;
    text-align: center;
}

.is-2 small {
    font-size: 1rem;
}
.specs-para {
    font-size: 0.8rem;
}
#sidebar {
  opacity: 0.5;
  color: #f0f0f0;
}
#reserveBtn {
   background-color: red;
   color: #f0f0f0;
   font-weight: 600;
   padding: 0 5% 0 5%;
}

/*Media queries*/

@media only screen and (max-width: 1100px) {
    .title1 {
    font-size: 1.2rem;
    }

    .title2 {
        font-size: 2.4rem;
    }

    .spec-detail {
        font-size: 1.5rem;
    }

    .spec-columns{
        width: 100%;
    }
    .heading-title {
        margin-top: 8%;
    }
}

@media only screen and (max-width: 750px) {
    .title1 {
    font-size: 1rem;
    }

    .title2 {
        font-size: 2rem;
    }

    .spec-detail {
        font-size: 1.2rem;
    }

    .spec-columns{
        width: 100%;
    }

    .specs-para {
        font-size: 0.6rem;
    }
    .heading-title {
        margin-top: 10%;
    }
}
</style>
