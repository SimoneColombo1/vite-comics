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

<cards />
</main>
</template>

<style scoped lang="scss">
main{
    background-color:#1c1c1c ;
    padding: 2rem;
    color: white;
}
</style>
