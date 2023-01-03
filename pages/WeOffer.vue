<template>
<div class="container">
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
</div>

<div class="mobile">
    <MobileHeader />
    <div class="mobile-offer">
        <h1>Наши услуги</h1>
        <div class="items">
            <div class="item">Создание Landing Page</div>
            <div class="item">Разработка интернет-магазина</div>
            <div class="item">Разработка корпоративного сайта</div>
            <div class="item">Индивидуальная разработка веб-сервисов</div>
            <div class="item">Разработка мобильных приложений</div>
            <div class="item">Выделенная команда разработчиков</div>
        </div>
        <img src="~/assets/mobileoffer.png" />
    </div>
    <MobileFooter />
</div>
</template>
<style scoped>
/* MOBILE */
@media screen and (max-width: 900px){
    .container{display: none;}
.mobile-offer{
    width: 100vw;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    position: relative;
    margin-top: 5vh;
}
h1{
    color: #460273;
    font-weight: bold;
    margin-bottom: 3vh;
}
img{
    width: 100%;
}
.items{
    position: absolute;
    bottom: 0;
    margin-bottom: 5.1vh;
    height: 81.3vh;
    width: 90vw;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.item{
    width: 100%;
    height: 13.5%;
    display: flex;
    align-items: center;
    justify-content: center;
}
}
/* WEB */
@media screen and (min-width: 900px){
.mobile{display: none;}
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
}
</style>