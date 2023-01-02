<template>
<div id="container">
    <div class="logo">LOGO</div>
    <nav>
        <NuxtLink to="/">Главная</NuxtLink>
        <NuxtLink to="/ourteam">Наша команда</NuxtLink>
        <NuxtLink to="/weoffer">Услуги</NuxtLink>
    </nav>
</div>
</template>
<style scoped>
#container{
    padding: 30px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
nav a{
    margin-right: 7vw;
    font-size: 2.2vw;
    font-weight: bold;
    text-decoration: none;
    color: #333B46;
}
.router-link-exact-active{
    color: #460273;
}
</style>