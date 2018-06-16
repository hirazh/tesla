<template>
    <section class="hero modelpage-wrapper bg-modelx">
        <div class="container heading-title" >
            <h3 class="title is-4" id="modelxTitle">Model X</h3>
            <h1 class="title is-1" id="modelxSubTitle">The Best SUV</h1>
        </div>
        <div class="container paragraph-wrapper">
            <!--
            <p class="para">
                The quickest car in the world, with record-setting<br> 
                acceleration, range and performance.
            </p>
            -->
        </div>
        <div class="container specs">
            <div class="columns spec-columns">
                <div class="column is-2 specs-wrapper">
                    <h1 class="spec-detail">5 <i class="fas fa-star fa-sm"></i></h1>
                    <p class="specs-para">five star safety</p>    
                </div>
                <div class="column is-1"><h1 class="title is-1 has-text-weight-light" id="sidebar">|</h1></div>
                <div class="column is-2">
                    <h1 class="spec-detail">7 <i class="fas fa-smile fa-sm"></i></h1>
                    <p class="specs-para">Room for seven</p>
                </div>
                <div class="column is-1"><h1 class="title is-1 has-text-weight-light" id="sidebar">|</h1></div>
                <div class="column is-2">
                    <h1 class="spec-detail">295<small>mi</small></h1>
                    <p class="specs-para">Mile Range</p>
                </div>
                <div class="column is-1"><h1 class="title is-1 has-text-weight-light" id="sidebar">|</h1></div>
                <div class="column is-2">
                    <div class="button is-rounded is-outlined" id="reserveBtn">Design yours</div>
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
.bg-modelx {
    background-image: url('../assets/images/modelX.jpg');
}

#modelxTitle, #modelxSubTitle {
    color: black;
}
</style>
