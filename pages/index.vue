<template>
<div class="container">
    <Header />
    <div class="chapter-introduction">
        <introdution />
    </div>

    <div class="chapter-howwework">
        <howwework />
    </div>

    <div class="chapter-whywe">
        <whywe />
    </div>

    <div class="footer">
        <Footer />
    </div>
</div>

<div class="mobile">
    <MobileHeader />
    <MobileIntrodution />
    <MobileHowwework />
    <MobileWhywe />
    <MobileFooter />
</div>
</template>
<script>
import { Icon } from '@iconify/vue';

export default {
    components: {
        Icon,
    },
};
</script>
<style scoped>
/* MOBILE */
@media screen and (max-width: 900px){
.container{display: none;}
.mobile{
    display: flex;
    flex-direction: column;
}
}
/* WEB */
@media screen and (min-width: 900px){
.mobile{display: none;}
.container{
    width: 100vw;
    height: 100vh;
    display: flex;
    flex-direction: column;
    color: #333B46;
}
.chapter-introduction{
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: right;
    margin-top: 6%;
}
.chapter-howwework{
    width: 100%;
    margin-top: 10%;
    display: flex;
    flex-direction: column;
}
.chapter-whywe{
    width: 100%;
    margin-top: 10%;
    display: flex;
    flex-direction: column;
}
.footer{
    width: 100%;
}
}
</style>