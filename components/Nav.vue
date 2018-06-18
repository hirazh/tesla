<template>
    <div class="columns is-marginless">
        <div class="column navbar-start nav-column is-3">
            <span class="navbar-item">
                <nuxt-link class="title brand-name" to="/">T E S L A</nuxt-link>
            </span>
        </div>
        <div class="column middle-nav nav-column">
            <nuxt-link class="navItem" to="/modelS">MODEL S</nuxt-link>
            <nuxt-link class="navItem" to="/modelX">MODEL X</nuxt-link>
            <nuxt-link class="navItem" to="/model3">MODEL 3</nuxt-link>
            <nuxt-link class="navItem" to="/roadster">ROADSTER</nuxt-link>
        </div>
        <div class="column navbar-end nav-column is-3">
            <span class="navItem">SHOP</span>
            <span class="navItem">SIGN IN</span>
            <span class="navItem"><i class="fas fa-bars"></i></span>
        </div>
    </div>
       
</template>

<script>
export default {};
</script>

<style>
.brand-name {
    font-size: 1.5rem;
}

.nav-column {
  display: flex;
  flex-direction: row;
  background-color: #4f4f4f;
  height: 10vh;
}
.middle-nav {
  justify-content: center;
  
}

.navItem {
  color: #f0f0f0;
  margin-left: 2%;
  margin-right: 2%;
}

.brand-name {
  color: #f0f0f0;
}

/*media queries*/

@media only screen and (max-width: 1100px) {
    .brand-name {
        font-size: 1rem;
    }
    .middle-nav {
        font-size: 14px;
    }

    .navbar-end {
        justify-content: center;
        font-size: 14px;
    }
}

@media only screen and (max-width: 950px) {
    .navbar-end {
        justify-content: center;
    }

    .navbar-end i{
        visibility: hidden;
    }
}

@media only screen and (max-width: 550px) {
      .brand-name {
        font-size: 1rem;
    }
    .middle-nav, .navbar-end {
        font-size: 12px;
    }
}
</style>
