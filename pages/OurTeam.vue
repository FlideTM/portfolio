<template>
<div class="container">
    <Header />
    <div class="team">
        <div class="content">
            <h1>Doc Ilizip - это команда профессианалов в своем деле</h1>
            <h2>Мы группа людей, объедененная пылающими глазами к своему делу, которые хотят внести свою лепту в развитее вашего бизнеса и IT индустрии в целом.<br />
            Наши работы - это мы сами, наш код - это не просто строчки букв и символов, наш код - это целое искусство, которое приследует оптимальное решение поставленных задач.<br />
            Оценить качество работы вы сможете ниже.</h2>
        </div>
        <img src="~/assets/ourteam.png" alt="doc ilizip's team" />
    </div>
    <Footer />
</div>

<div class="mobile">
    <MobileHeader />
    <div class="mobile-team">
        <div class="content">
            <h1>Doc Ilizip - это команда профессианалов в своем деле</h1>
            <h2>Мы группа людей, объедененная пылающими глазами к своему делу, которые хотят внести свою лепту в развитее вашего бизнеса и IT индустрии в целом.<br />
            Наши работы - это мы сами, наш код - это не просто строчки букв и символов, наш код - это целое искусство, которое приследует оптимальное решение поставленных задач.<br />
            Оценить качество работы вы сможете ниже.</h2>
        </div>
        <img src="~/assets/ourteam.png" alt="doc ilizip's team" />
    </div>
    <MobileFooter />
</div>
</template>
<style scoped>

/* MOBILE */
@media screen and (max-width: 900px){
.container{display: none;}
.mobile-team{
    display: flex;
    flex-direction: column;
    width: 90vw;
    margin-left: auto;
    margin-right: auto;
    justify-content: center;
    align-items: center;
    text-align: center;
    margin-top: 5vh;
    margin-bottom: 5vh;
}
.content{
    width: 100%;
    color: #333B46;
    font-size: 3vw;
}
h1{
    color: #460273;
    font-size: 7vw;
    margin-bottom: 3vh;
}
img{ 
    width: 100%; 
    margin-top: 2vh;
}
}

/* WEB */
@media screen and (min-width: 900px){
.mobile{display: none;}
.team{
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: right;
    margin-top: 18vh;
    margin-bottom: 16vh;
}
img{
    margin-right: 3vw;
    width: 50vw;
}
.content{
    position: absolute;
    width: 46vw;
    left: 0;
    margin-left: 5vw;
    height: 26vw;
    margin-top: 5vw;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
}
.content h1{
    color: #460273;
    font-size: 2vw;
    font-weight: bold;
}
.content h2{
    color: #333B46;
    font-size: 1.5vw;
}
}
</style>