<script>
import cards from './cards.vue';


export default{
    data() {
        return {
            
        }
    },
    components:{
        cards,
        
    }
}

</script>

<template>

<main>
<div class="jumbo-background">
<span><h3>CURRENT SERIES</h3></span>
</div>
<cards />
</main>
</template>

<style scoped lang="scss">
main{
    background-color:#1c1c1c ;
   
    color: white;
}
.jumbo-background{
    background-image: url(../assets/img/jumbotron.jpg);
    width: 100vw;
    height: 30rem;
    display: flex;
    background-size: cover;

    span{
        display: flex;
        
        padding: .5rem;
        
        background-color: #0282f9;
        color: white;
        position: absolute;
        left: 23rem;
        top: 37.5rem;
        text-align: center;
    }
    
}
</style>
