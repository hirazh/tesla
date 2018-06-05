<template>
  <div>
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

.modelpage-wrapper {
    background-size: cover;
    text-align: center;
    height: 90vh;
}
.title {
    color: #f0f0f0;
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
}
.specs {
    margin-bottom: 3%;
    display: flex;
    justify-content: space-around;
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
}
#reserveBtn {
   margin-top: 20%;
   padding: 0 15% 0 15%;
}

</style>
