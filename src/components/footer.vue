<template lang="">
        <div class="footer">
                <div class="Aloha-footer-1">
                 <ul>
                    <li class="aloha-foooter-li">© Aloha</li>
                    <li class="aloha-foooter-li">Powered by Webflow</li>
                 </ul>
                 <img class="palma" src="@/assets/Vector.svg">
                </div>
                <div class="Aloha-footer">
                    <ul>
                        <li class="aloha-foooter-li">About</li>     
                        <li class="aloha-foooter-li">Contact</li>
                        <li class="aloha-foooter-li">Licenses</li>
                        <li class="aloha-foooter-li">Style Guide</li>
                        <li class="aloha-foooter-li">Changelog</li>
                        <li class="aloha-foooter-li">Password</li>
                        <li class="aloha-foooter-li">404</li>
                    </ul>
                </div>
                <div class="Aloha-footer">
                    <ul>
                        <li class="aloha-foooter-li">Home 1</li>
                        <li class="aloha-foooter-li">Home 2</li>
                        <li class="aloha-foooter-li">Work 1</li>
                        <li class="aloha-foooter-li">Work 2</li>
                        <li class="aloha-foooter-li">Blog 1</li>
                        <li class="aloha-foooter-li">Blog 2</li>
                    </ul>
                </div>
                <div class="Aloha-footer">
                    <ul>
                        <li class="aloha-foooter-li">Twitter</li>
                        <li class="aloha-foooter-li">Instagram</li>
                        <li class="aloha-foooter-li">Instagram</li>
                    </ul>
                </div>
            </div>
    
</template>
<script>
export default {
    
}
</script>
<style scoped>
.footer {
    display: flex;
    justify-content: space-between;
    margin-top: 200px;
    padding-bottom: 100px;
}
.aloha-foooter-li {
    list-style: none;
font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 29px;
}
.palma {
    margin-top: 80px;
}
.Aloha-footer-1{
    flex-basis: 30%;
} 
</style>