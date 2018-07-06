<template>
    <section class="modelpage-wrapper model3-wrapper">
        <div class="vedio-wrapper">
            <video width="cover" height="auto" autoplay loop>
            <source src="../assets/images/Model3-vedio.mp4">
            </video>
            <div class="text-wrapper">
                <h1 class="title">Model 3</h1>
                <p>
                    Designed to attain the highest safety ratings in every category,<br> 
                    Model 3 achieves 220 miles of range while starting at only $35,000 before incentives.
                </p>
                <button class="button" id="model3btn">RESERVE YOURS</button>
            </div>
        </div>
    </section>    
</template>

<script>
export default {
    
}
</script>


<style>
.model3-wrapper {
    position: relative;
    background-color: #4f4f4f;
    display: flex;
    align-items: center;
    justify-content: center;
}

.text-wrapper{
    position: absolute;
    top: 25%;
    left: 0;
    right: 0;
}

.text-wrapper h1, p {
    color: #f0f0f0;
}

#model3btn {
    background-color: red;
    color: #f0f0f0;
    margin-top: 3%;
}

@media only screen and (max-width: 750px) {
    .text-wrapper{
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
    }

    .text-wrapper p {
        font-size: 12px;
        margin-left: 10%;
        margin-right: 10%;
        margin-bottom: 5%;
    }
}
</style>
