<template lang="">
        <div class="content">
            <div class="work">
            <h1 class="title-text">I help emerging brands get their footing in today's digital world.</h1>
            <div class="btn-work">
            <a class="btn-all" href="@">See my work</a>
            </div>
            </div>
            <div class="travelblog">
                <div class="biscle-img">
                    <img src="@/assets/biscle.png" width="100%" height="100%">
                </div>
                <div class="travel-content">
                    <p class="text-all">My services are perfect for <br>companies that are just getting started</p>
                    <a class="btn-all" href="@">Learn more</a>
                </div>
            </div>
            <div class="travelblog">
                <div class="travel-content">
                    <p class="text-all">I'm always on the go. Follow along!</p>
                    <a class="btn-all" href="@">@aloha</a>
                </div>
                <div class="biscle-img">
                    <img src="@/assets/auto.png" width="100%" height="100%">
                </div>
                
            </div>
        </div>  
</template>
<script>
export default {
    
}
</script>
<style>
.btn-all {
border: 2px solid #4B321D;
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 29px;
text-decoration: none;
color: #4B321D;
padding: 10px 17px;
margin-top: 50px;
}  
.travelblog {
    display: flex;
    justify-content: space-between;
    align-items: center;    
    gap: 60px;
    margin-top: 90px;
}
.text-all {
font-style: normal;
font-weight: 400;
font-size: 38px;
line-height: 44px;
margin-bottom: 50px;
}
.btn-work {
    margin-top: 50px;
}

    
</style>