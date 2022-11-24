<template>
    <div class="conteiner">
        
        <burgerVue/>
        <div id="page-wrap">
        <headerVue/>
        
       <div class="title">
            <h1 class="title-text">Creating purpose-built brands & websites</h1>
        </div>
        </div>
        
        <div class="image-big-header">
            <img class="img-head" src="./assets/IMAGE.png" width="100%" alt="Man look in window"/>
        </div>
        <div class="conteiner">
        <contentVue/>
        </div>
        
        <downVue/>
        <div class="conteiner">
            <div class="down-content">
                    <p class="title-text" id="position-down-content">Seem like a good fit?</p>
                    <a class="btn-all" href="@">Let's talk!</a>
                </div>
        </div>
        <div class="conteiner">
            <footerVue/>
        </div>
    </div>
      


</template>
<script>
import headerVue from "./components/header.vue";
import burgerVue from './components/burger.vue';
import footerVue from './components/footer.vue';
import contentVue from './components/conten.vue';
import downVue from "./components/down.vue";
export default {
    components: {
        headerVue, burgerVue, footerVue, contentVue,downVue
    }
}
</script>
<style>
*{
padding: 0px;
margin: 0px;
}
body{
    background-color: #E5E5E5;
}
.conteiner {
    margin: 0px 60px;
    font-family: 'Poppins', 'san - serif';
}

.title-text {
    font-style: normal;
    font-weight: 400;
    font-size: 80px;
    line-height: 100px;
    color: #4B321D;

}
.title {
    margin-top: 125px;
}
.image-big-header {
    
    margin: 130px 20px 80px 20px;
    
}
.img-head {
    width: 100%;
}

.xyexye {
    display: flex;
    justify-content: space-between;
}

</style>