<template>
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
.header{
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.header h1{
    color: #460273;
    font-size: 3vw;
    text-align: center;
}
.header h2{
    margin-top: 1%;
    font-size: 1.75vw;
    text-align: center;
}
.elements{
    margin-top: 1%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    width: 100%;
    justify-content: space-between;
    text-align: center;
}
.element{
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    width: 20%;
    padding: 1%;
}
.icon{
    color: #460273;
    font-size: 5vw;
}
.h1{
    color: #333B46;
    font-size: 2vw;
    font-weight: bold;
}
.h2{
    color: #333B46;
    font-size: 1.5vw;
}
</style>