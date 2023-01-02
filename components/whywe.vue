<template>
<div class="whywe">
    <h1>Почему именно мы?</h1>
    <div class="contents">
        <img src="~/assets/asset2.png" alt="doc ilizip" />
        <nav class="nav">
            <li>"Одни из многих" - это про нас!</li>
            <li>Если вам необходимо сочетание технологий, маркетинга и дизайна, вы попали по адресу.</li>
            <li>Наши работы - это сочетание верных решений, полета мысли и лучшей разработки.</li>
            <li>Наша цель - помочь вам в достижении ваших бизнес идей.</li>
            <li>Для простоты работы мы создали своего бота, в котором вы сможете оформить заказ в максимально короткое время. Никнейм бота: @sosi_chert</li>
        </nav>
    </div>
</div>
</template>
<style scoped>
.whywe{
    width: 100%;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
}
h1{
    width: 100%;
    font-size: 3.3vw;
    text-align: center;
    color: #460273;
}
.contents{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-top: 2%;
}
img{
    width: 80%;
}
.nav{
    margin-left: 2%;
}
.nav li{
    font-size: 2vw;
    margin-bottom: 1.5%;
}
</style>