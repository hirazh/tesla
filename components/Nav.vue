<template>
    <div class="columns is-marginless">
        <div class="column navbar-start nav-column">
            <span class="navbar-item">
                <nuxt-link class="title is-4 brand-name" to="/">T E S L A</nuxt-link>
            </span>
        </div>
        <div class="column middle-nav nav-column">
            <span class="navbar-item">MODEL S</span>
            <span class="navbar-item">MODEL X</span>
            <span class="navbar-item">MODEL 3</span>
            <nuxt-link class="navbar-item" to="/roadster">ROADSTER</nuxt-link>
        </div>
        <div class="column navbar-end nav-column">
            <span class="navbar-item">SHOP</span>
            <span class="navbar-item">SIGN IN</span>
            <span class="navbar-item"><i class="fas fa-bars"></i></span>
        </div>
    </div>
       
</template>

<script>
export default {};
</script>

<style>
.nav-column {
  display: flex;
  flex-direction: row;
  background-color: #4f4f4f;
  height: 10vh;
}
.middle-nav {
  justify-content: center;
}

.navbar-item {
  color: #f0f0f0;
}

.brand-name {
  color: #f0f0f0;
}

</style>
