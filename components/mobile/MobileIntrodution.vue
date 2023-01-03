<template>
<div class="mobile-container">
    <div class="text-introdution">
    <span class="h1">Веб-студия "doc ilizip"</span>
    <span class="h2">Решения любой сложности</span>
    <span>Наша команда разрабатывает сайты любой сложности, серверную архитектуру, мобильные приложения. Мы можем воплотить в жизнь ваши самые амбициозные идеи.</span>
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
    <img src="~/assets/asset.png" />
</div>
</div>
</template>

<script>
import { Icon } from '@iconify/vue';
export default{
    components:{
        Icon,
    }
}
</script>

<style scoped>
.mobile-container{
    margin-top: 5vh;
    width: 100vw;
}
.text-introdution{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}
.h1{
    color: #460273;
    font-size: 8vw;
}
.h2{
    color: #333B46;
    font-size: 6vw;
    margin-top: 1vh;
    margin-bottom: 1vh;
}
span{
    color: #333B46;
    font-size: 4vw;
}
table{
    color: #333B46;
    font-size: 4vw;
    margin-top: 1vh;
    margin-bottom: 1vh;
}
table span{
    color: #460273;
}
img{
    margin-top: 1vh;
    width: 80%;
}
</style>