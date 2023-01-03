<template>
<div class="mobile-container">
    <div class="header">
        <h1>Как мы работаем</h1>
        <h2>Простая схема работы с нами</h2>
    </div>
    <div class="elements">
        <div class="element">
            <span class="icon"><Icon icon="jam:phone-f" /></span>
            <span class="h1">Заказ</span>
            <span class="h2">Оформляем договор и вносится предоплата</span>
        </div>
        <div class="element">
            <span class="icon"><Icon icon="material-symbols:design-services" /></span>
            <span class="h1">Дизайн</span>
            <span class="h2">Разрабатываем и согласовываем вместе дизайн вашего проекта</span>
        </div>
        <div class="element">
            <span class="icon"><Icon icon="mdi:cog" /></span>
            <span class="h1">Разработка</span>
            <span class="h2">Разрабатываем сайт с учетом ваших пожеланий и исправлений</span>
        </div>
        <div class="element">
            <span class="icon"><Icon icon="ph:monitor-fill" /></span>
            <span class="h1">Перенос</span>
            <span class="h2">Полная оплата, перенос уже выполненного проекта на хостинг заказчика</span>
        </div>
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
.mobile-container{
    width: 90vw;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #333B46;
    margin-top: 5vh;
    margin-left: auto;
    margin-right: auto;
}
h1{
    color: #460273;
    font-size: 7vw;
}
h2{
    font-size: 5vw;
    margin-top: 3vh;
}
.element{
    
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 3vh;
}
.icon{
    font-size: 10vw;
    color: #460273;
}
.h1{
    font-size: 6vw;
    margin-top: 1vh;
    margin-bottom: 1vh;
    font-weight: bold;
}
.h2{
    font-size: 3vh;
}
</style>