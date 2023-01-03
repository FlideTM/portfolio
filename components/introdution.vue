<template>
<div id="text-introdution">
    <h1>Веб-студия "doc ilizip"</h1><br />
    <h2>Веб решения любой сложности</h2><br />
    <p>Наша команда разрабатывает сайты любой сложности, серверную архитектуру, мобильные приложения. Мы можем воплотить в жизнь ваши самые амбициозные идеи.</p><br />
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
<img src="~/assets/asset.png" alt="doc ilizip" />
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
img{
    width: 50vw;
    margin-right: 9%;
}
#text-introdution{
    position: absolute;
    width: 40%;
    left: 0;
    margin-left: 9%;
    margin-top: 6%;
    display: flex;
    flex-direction: column;
}
#text-introdution h1{
    font-size: 3.7vw;
    width: 100%;
    color: #460273;
}
#text-introdution h2{
    font-size: 2.3vw;
}
#text-introdution p{
    font-size: 1.5vw;
}
#text-introdution table{
    font-size: 1.5vw;
}
table span{
    color: #460273;
}
</style>