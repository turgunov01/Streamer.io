<template>
    <div class="aside-logo">
        <img src="/assets/logo-person.svg" class="aside-logo-image person-logo" alt="">

        <button>
            <img src="/assets/back.svg" alt="">
        </button>
    </div>
    <ul class="aside-list">
        <li class="aside-item">
            <nuxt-link to="/live" class="aside-link">
                <img src="/assets/sidebar/stream.svg" alt="">
                <p class="aside-item-name">Лайв стрим</p>
            </nuxt-link>
            <nuxt-link to="/mission" class="aside-link between">
                <p class="aside-item-name">Задание за баллы</p>
                <img src="/assets/sidebar/chevron.svg" alt="">
            </nuxt-link>
            <nuxt-link to="/" class="aside-link">
                <img src="/assets/sidebar/games.svg" alt="">
                <p class="aside-item-name">Игры</p>
            </nuxt-link>
            <nuxt-link to="/partners" class="aside-link">
                <img src="/assets/sidebar/partners.svg" alt="">
                <p class="aside-item-name">Наши партнеры</p>
            </nuxt-link>
            <nuxt-link to="/shop" class="aside-link">
                <img src="/assets/sidebar/shop.svg" alt="">
                <p class="aside-item-name">Магазин</p>
            </nuxt-link>
            <nuxt-link to="/statistics" class="aside-link">
                <img src="/assets/sidebar/statistics.svg" alt="">
                <p class="aside-item-name">Статистика</p>
            </nuxt-link>
            <nuxt-link to="/news" class="aside-link">
                <p class="aside-item-name">Новые видео и новости</p>
            </nuxt-link>
            <nuxt-link to="/history" class="aside-link">
                <p class="aside-item-name">Прошлые стримы</p>
            </nuxt-link>
            <nuxt-link to="/" class="aside-link">
                <p class="aside-item-name">Правила</p>
            </nuxt-link>
        </li>
    </ul>
</template>


<script lang="ts" setup>


</script>

<style scoped lang="scss">
.person-logo {
    max-width: 4.1rem;
    width: 100%;
}
</style>