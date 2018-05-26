<template>
    
        <div class="columns is-marginless">
            <div class="column navbar-start">
                <span class="navbar-item">
                    <h1 class="title is-4 brand-name">T E S L A</h1>
                </span>
            </div>
            <div class="column middle-nav">
                <span class="navbar-item">MODEL S</span>
                <span class="navbar-item">MODEL X</span>
                <span class="navbar-item">MODEL 3</span>
                <span class="navbar-item">ROADSTER</span>
            </div>
            <div class="column navbar-end">
                <span class="navbar-item">SHOP</span>
                <span class="navbar-item">SIGN IN</span>
                <span class="navbar-item"><i class="fas fa-bars"></i></span>
            </div>
        </div>
       
</template>

<script>
export default {
    
}
</script>

<style>

.column {
    display: flex;
    flex-direction: row;
    background-color: #4F4F4F;
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
