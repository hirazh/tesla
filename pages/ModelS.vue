<template>
    <section class="hero modelpage-wrapper bg-models">
        <div class="container heading-title">
            <h3 class="title1">Model S</h3>
            <h1 class="title2">The Best Car</h1>
        </div>
        <div class="actionbtn">
            <div class="button is-rounded" id="reserveBtn">Design yours</div>
        </div>
        <div class="container specs">
            <div class="columns spec-columns">
                <div class="column specs-wrapper">
                    <h1 class="spec-detail">2.5<small>s</small></h1>
                    <p class="specs-para">from 0-60 mph</p>    
                </div>
                <div class="column"><h1 class="title is-1 has-text-weight-light" id="sidebar">|</h1></div>
                <div class="column">
                    <h1 class="spec-detail">5 <i class="fas fa-star fa-sm"></i></h1>
                    <p class="specs-para">five star safety</p>
                </div>
                <div class="column"><h1 class="title is-1 has-text-weight-light" id="sidebar">|</h1></div>
                <div class="column">
                    <h1 class="spec-detail">335<small>mi</small></h1>
                    <p class="specs-para">Mile Range</p>
                </div>
                <!--
                <div class="column"><h1 class="title is-1 has-text-weight-light" id="sidebar">|</h1></div>
                <div class="column">
                    <div class="button is-rounded is-outlined" id="reserveBtn">Design yours</div>
                </div>
                -->
            </div>
        </div>
    </section>
</template>

<script>
export default {
  
  
}
</script>

<style>
.bg-models {
    background-image: url('../assets/images/model-s-white.jpg');
    background-position: center center;
}
#star-icons {
    display: inline-block;
}
</style>
