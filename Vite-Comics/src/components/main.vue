<script>
import cards from './cards.vue';
export default{
    data() {
        return {
            
        }
    },
    components:{
        cards
    }
}

</script>

<template>
<main>
<h1> ---> Contens Goes Here <---</h1>
<cards />
</main>
</template>

<style scoped>
main{
    background-color:#1c1c1c ;
    padding: 2rem;
    color: white;
}
</style>
