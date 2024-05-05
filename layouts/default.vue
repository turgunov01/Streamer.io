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
            <FooterComponent />
        </div>
    </div>
</template>

<script lang="ts" setup>
import FooterComponent from '../components/FooterComponent.vue'
import Navigation from '~/components/Navigation.vue';

</script>

<style scoped lang="scss"></style>