<template>
    <section class="hero modelpage-wrapper bg-roadster">
        <div class="container heading-title">
            <h3 class="title1">Tesla</h3>
            <h1 class="title2">Roadster</h1>
        </div>
        <div class="actionbtn">
            <div class="button is-rounded is-outlined" id="reserveBtn">Design yours</div>
        </div>
        <div class="container paragraph-wrapper">
            <p class="para">
                The quickest car in the world, with record-setting<br> 
                acceleration, range and performance.
            </p>
        </div>
        <div class="container specs">
            <div class="columns spec-columns">
                <div class="column  specs-wrapper">
                    <h1 class="spec-detail">1.9<small>s</small></h1>
                    <p class="specs-para">0-60mph</p>    
                </div>
                <div class="column"><h1 class="title is-1 has-text-weight-light" id="sidebar">|</h1></div>
                <div class="column">
                    <h1 class="spec-detail"><small>+</small>250<small>mph</small></h1>
                    <p class="specs-para">Top Speed</p>
                </div>
                <div class="column"><h1 class="title is-1 has-text-weight-light" id="sidebar">|</h1></div>
                <div class="column">
                    <h1 class="spec-detail">620<small>mi</small></h1>
                    <p class="specs-para">Mile Range</p>
                </div>
                
            </div>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style>
.bg-roadster {
    background-image: url('../assets/images/Roadster.jpg');
    background-size: cover;
    background-position: center center;
}
</style>

