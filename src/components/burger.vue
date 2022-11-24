<template lang="">
    <div>
        <Push>
            <ul class="nav-burger">
                <li class="nav-menu" ><a href="#">Projects</a></li>
                <li class="nav-menu" ><a href="#">About</a></li>
                <li class="nav-menu" ><a href="#">Blog</a></li>
                <li class="nav-menu" ><a href="#">Contact</a></li>
                
            </ul>
        </Push>
    </div>
</template>
<script>
import { Push} from 'vue3-burger-menu'  

export default {
    components: {
        Push
}
}

</script>
<style >
.bm-burger-button{
    display: none;
}
   .nav-burger {
    display: block;
} 
@media (max-width: 600px) {
    .bm-burger-button {
        position: relative;
        display: flex;
        align-items: flex-end;
        
    }
}
</style>
