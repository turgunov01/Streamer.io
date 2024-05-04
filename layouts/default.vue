<template>
    <div class="wrapper">
        <div class="aside-parent">
            <aside class="aside">
                <Navigation />
            </aside>
        </div>
        <div class="content">
            <nav class="nav">
                <div class="nav-container">
                    <div class="nav-logo">
                        <img src="/assets/logo-word.svg" alt="">
                    </div>
                    <div class="nav-points">
                        <p class="nav-point">0</p>
                        <img src="/assets/points.svg" alt="">
                    </div>
                    <div class="nav-login">
                        <button class="nav-login-button">Войти</button>
                    </div>
                </div>
            </nav>
            <main class="main-container">
                <slot />
            </main>
            <footer class="footer">
                <div class="container">
                    <div class="footer-logo-row">
                        <img src="/assets/logo-person.svg" class="person-logo" alt="">
                        <img src="/assets/logo-word.svg" class="word-logo" alt="">
                    </div>
                    <div class="footer-logo-row">
                        <ul class="footer-list">
                            <li class="footer-item">
                                <nuxt-link to="/">Главная</nuxt-link>
                            </li>
                            <li class="footer-item">
                                <nuxt-link to="/live">Лайв стрим</nuxt-link>
                            </li>
                            <li class="footer-item">
                                <nuxt-link to="/">Задания за баллы</nuxt-link>
                            </li>
                            <li class="footer-item">
                                <nuxt-link to="/">Игры</nuxt-link>
                            </li>
                        </ul>
                    </div>
                    <div class="footer-logo-row">
                        <ul class="footer-list">
                            <li class="footer-item">
                                <nuxt-link to="/">Наши партнеры</nuxt-link>
                            </li>
                            <li class="footer-item">
                                <nuxt-link to="/">Магазин</nuxt-link>
                            </li>
                            <li class="footer-item">
                                <nuxt-link to="/">Статистика</nuxt-link>
                            </li>
                            <li class="footer-item">
                                <nuxt-link to="/">Правила</nuxt-link>
                            </li>
                        </ul>
                    </div>
                    <div class="footer-logo-row">
                        <ul class="footer-list">
                            <li class="footer-item">
                                <nuxt-link to="/">Новые видео и новости</nuxt-link>
                            </li>
                            <li class="footer-item">
                                <nuxt-link to="/">Прошлые стримы</nuxt-link>
                            </li>
                        </ul>
                    </div>
                    <div class="footer-logo-row media">
                        <h2 class="footer-row-name">Соцсети</h2>
                        <ul class="footer-row-medias">
                            <li class="footer-row-media">
                                <img src="/assets/kick.svg" alt="">
                            </li>
                            <li class="footer-row-media">
                                <img src="/assets/telegram.svg" alt="">
                            </li>
                            <li class="footer-row-media">
                                <img src="/assets/youtube-transparent.svg" alt="">
                            </li>
                        </ul>
                    </div>
                </div>
            </footer>
        </div>
    </div>
</template>

<script lang="ts" setup>

import Navigation from '~/components/Navigation.vue';

</script>

<style scoped lang="scss"></style>