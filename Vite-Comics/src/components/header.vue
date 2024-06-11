<script>

</script>

<template>
<header>
    <div class="Header-container">
        <div class="DC-Logo">DC</div>
        <ul>
            <li>
               <a href="">       CHARACTERS</a>
            </li>
            <li class="active">
             <a href="" >  COMICS</a>
            </li>
            <li>
            <a href=""> MOVIES</a> 
             </li>
              <li>
            <a href="">  TV </a>  
            </li>
              <li>
           <a href="">  GAMES</a>
              </li>
             <li>
           <a href="">COLLECTIBLES</a> 
           </li>
          <li>
         <a href=""> VIDEOS</a>
            </li>
         <li>
     <a href=""> FANS</a>
         </li>
         <li>
        <a href="">NEWS</a>
           </li>
         <li>
     <a href="">SHOP </a>
        </li>
        </ul>
    </div>
</header>
</template>

<style scoped>

.Header-container{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    background-color: #ffffff;
    padding: 2rem;
}
.Header-container ul{
display: flex;
flex-direction: row;

}
.Header-container li{
list-style: none;
margin: 0 1rem;
padding: 1rem 0;
}

.Header-container a:hover{
    color:#0282f9;
}



.Header-container a{
    color:#58595d ;
}
.active{
   
    border-bottom: #0282f9 solid 3px;
    
}
.active a{
    color: #0282f9;
}


</style>
