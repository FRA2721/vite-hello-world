<!-- script -->
<script>
export default{
    name: "AppHero",
    data(){
        return{
           text: "RED DICE",
        }
    }
}
</script>
<!-- /script -->



<!-- template-section -->
<template>
    <div class="jumbotron">
        <img src="../assets/dice.jpg" alt="dice image">
        <div class="jumbo-text">
            <h1>{{ text }}</h1>
            <p>Francesco Cimino classe#73... DIce jumbotron</p>
        </div>
    </div>
</template>
<!-- /template-section -->



<!-- style -->
<style scoped>
.jumbotron{
    width: 100%;
    height: 393px;
    position: relative;
}
.jumbotron img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.jumbotron .jumbo-text{
    top: 3px;
    right: 33px;
    color: white;
    text-align: right;
    position: absolute;
}
</style>
<!-- /style -->