<template>
    <section class="hero roadsterpage-wrapper">
        <div class="container heading">
            <h3 class="title is-5">Tesla</h3>
            <h1 class="title is-1">Roadster</h1>
        </div>
        <div class="container paragraph-wrapper">
            <p class="para">
                The quickest car in the world, with record-setting<br> 
                acceleration, range and performance.
            </p>
        </div>
        <div class="container specs">
            <div class="columns spec-columns">
                <div class="column is-2">
                    <h1>1.9<small>s</small></h1>
                    <p>0-60mph</p>    
                </div>
                <div class="column is-1"><h1 class="title is-1" id="sidebar">|</h1></div>
                <div class="column is-2">
                    <h1><small>+</small>250<small>mph</small></h1>
                    <p>Top Speed</p>
                </div>
                <div class="column is-1"><h1 class="title is-1" id="sidebar">|</h1></div>
                <div class="column is-2">
                    <h1>620<small>mi</small></h1>
                    <p>Mile Range</p>
                </div>
                <div class="column is-1"><h1 class="title is-1" id="sidebar">|</h1></div>
                <div class="column is-2">
                    <div class="button">Reserve Now</div>
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
.roadsterpage-wrapper {
    background-image: url('../assets/images/Roadster.jpg');
    background-size: cover;
    text-align: center;
    height: 90vh;
}
.title {
    color: #f0f0f0;
}
.heading {
    margin-top: 3%;
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
}
.specs {
    margin-bottom: 3%;
    display: flex;
    justify-content: space-around;
}

</style>

