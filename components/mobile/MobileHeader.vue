<template>
    <div class="mobile-header">
        <div class="logo">logo</div>
        <nav class="nav">
            <NuxtLink to="/">Главная</NuxtLink>
            <NuxtLink to="/ourteam">Наша команда</NuxtLink>
            <NuxtLink to="/weoffer">Услуги</NuxtLink>
        </nav>
    </div>
</template>
<style scoped>
.mobile-header{
    width: 100vw;
    height: 20vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.logo{
    width: 90%;
    height: 100%;
    margin-left: auto;
    margin-right: auto;
    display: flex;
    justify-content: center;
    align-items: center;
}
.nav{
    width: 90%;
    margin-left: auto;
    margin-right: auto;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-between;
}
nav a{
    font-weight: bold;
    text-decoration: none;
    color: #333B46;
}
.router-link-exact-active{
    color: #460273;
}
</style>