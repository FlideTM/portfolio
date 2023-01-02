<template>
    <Header />
    <div class="offer">
        <h1>Наши услуги</h1>
        <div class="items">
            <div class="item">Создание Landing Page</div>
            <div class="item">Разработка интернет-магазина</div>
            <div class="item">Разработка корпоративного сайта</div>
            <div class="item">Индивидуальная разработка веб-сервисов</div>
            <div class="item">Разработка мобильных приложений</div>
            <div class="item">Выделенная команда разработчиков</div>
        </div>
        <img src="~/assets/offer.png">
    </div>
    <Footer />
</template>
<style scoped>
.offer{
    width: 100vw;
    display: flex;
    flex-direction: column;
    margin-top: 18vh;
}
h1{
    color: #460273;
    font-weight: bold;
    text-align: center;
    font-size: 3vw;
}
img{
    margin-top: 5vh;
}
.items{
    position: absolute;
    margin-left: 9.8vw;
    margin-top: 11.1vw;
    width: 80.3vw;
    height: 18.4vw;
    display: flex;
    row-gap: 2.75vw;
    flex-wrap: wrap;
    justify-content: space-between;
}
.item{
    border-radius: 20px;
    width: 24.8vw;
    height: 7.7vw;
    align-items: center;
    justify-content: center;
    text-align: center;
    display: flex;
    color: #333B46;
    font-weight: bold;
    font-size: 1.3vw;
}
</style>