<template lang="">
    <div>
        <div class="header">
        <div class="aloha">
            <img class="aloha-img" src="@/assets/Group.svg" alt="aloha"/>
        </div>
        <div class="menu">
          
        <ul class="nav">
                <li class="nav-menu" ><a href="#">Projects</a></li>
                <li class="nav-menu" ><a href="#">About</a></li>
                <li class="nav-menu" ><a href="#">Blog</a></li>
                <li class="nav-menu" ><a href="#">Contact</a></li> 
            </ul>
        </div>
    </div>
    </div>
</template>
<script>

</script>
<style scoped>
.header {
    display: flex;
    justify-content: space-between  ;
    margin-top: 50px;
}
.nav {
    display: flex;
    margin-right: 343px;
}
.nav-menu {
    
    list-style-type: none;
    margin-right: 40px;
    font-style: normal;
    font-weight: 400;
     font-size: 18px;
    line-height: 29px;
    
}
.nav-menu a{
    text-decoration: none;
    color: #4B321D;}
    @media (max-width: 600px) {
    .header {
        display: none;
    }
        
    }

</style>