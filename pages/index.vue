<template>
<div class="container">
    <Header />

    <div class="chapter-introduction">
        <div id="text-introdution">
            <h1>Веб-студия "doc ilizip"</h1><br />
            <h2>Веб решения любой сложности</h2><br />
            <p>Наша команда разрабатывает сайты любой сложности, серверную архитектуру, мобильные приложения. Мы можем воплотить в жизнь ваши самые амбициозные идеи.<br /></p><br />
            <table>
                <tr>
                    <th>Телефон:</th>
                    <td><span><Icon icon="fluent-emoji-high-contrast:telephone-receiver" /></span>+7 (912) 030 83-84 (MTC)</td>
                </tr>
                <tr>
                    <td></td>
                    <td><span><Icon icon="fluent-emoji-high-contrast:telephone-receiver" /></span>+7 (911) 113 33-17 (Tele2)</td>
                </tr>
            </table>
        </div>
        <img src="~/assets/asset.png" alt="Discover Nuxt 3" />
    </div>

    <div class="chapter-howwework">
        howwework
    </div>

    <div class="chapter-whywe">
        whywe
    </div>

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
    margin-top: 100px;
}
.chapter-introduction img{
    width: 1000px;
    margin-right: 150px;
}
#text-introdution{
    position: absolute;
    width: 800px;
    left: 0;
    margin-left: 150px;
    margin-top: 90px;
}
#text-introdution h1{
    font-size: 76px;
    color: #460273;
}
#text-introdution h2{
    font-size: 40px;
}
#text-introdution p{
    font-size: 30px;
}
#text-introdution table{
    font-size: 30px;
}
table span{
    color: #460273;
}
.chapter-howwework{
    width: 100%;
    border: 1px solid black;
    height: 20%;
}
.chapter-whywe{
    width: 100%;
    border: 1px solid black;
    height: 20%;
}
</style>