<script>

</script>

<template>
<nav class="Search">
    
    <button class="sign-in">SIGN-UP NOW!</button>
      
    <ul class="socials">
        <li>
    <h2> FOLLOW US</h2> 
        </li>
        <li>
           <img src="../assets/img/footer-facebook.png">
        </li>
        <li>
           <img src="../assets/img/footer-twitter.png">
        </li>
        <li>
           <img src="../assets/img/footer-youtube.png">
        </li>
        <li>
            <img src="../assets/img/footer-pinterest.png">
        </li>
        <li>
            <img src="../assets/img/footer-periscope.png">
        </li>
       </ul> 

</nav>
</template>

<style scoped>
.Search{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    background-color: #303030;
    padding: 2rem;
}

.socials{
    display: flex;
    flex-direction: row;
}
.socials li{
    list-style: none;
    padding: 1rem;
}
.socials h2{
    color: #0777df;
}
.Search button{
    width: 8rem;
    height: 3rem;
    background-color: #303030;
    border: solid 2px #0777df;
    color: white;
    
}
.Search button:hover{
    background-color: #0777df;
}
</style>
