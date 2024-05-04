<template>
    <div class="stream">
        <h2 class="stream-title">Лайв стрим</h2>
        <p class="stream-description">Смотрим и играем вместе</p>
        <div class="media">
            <StreamComponent />
        </div>
        <div class="stream-content">
            <div class="box">
                <div class="stream-desk">
                    <p class="stream-desk-name">Прогнозы</p>
                    <div class="stream-desk-banner">Сколько даст слот?</div>
                </div>
                <div class="stream-desk-percents">
                    <div class="stream-desk-bets">
                        <p class="stream-desk-bet">в минус</p>
                        <p class="stream-desk-bet">х0</p>
                        <p class="stream-desk-bet">х5-10</p>
                        <p class="stream-desk-bet">Больше х10</p>
                    </div>
                    <div class="stream-play">
                        <img src="/assets/play.svg" class="stream-play-icon" alt="">
                    </div>
                </div>
                <div class="stream-desk-timer">
                    {{ new Date().getHours() }}:{{ new Date().getMinutes() < 10 ? '0' : '' }}{{ new Date().getMinutes()
                        }}:{{ new Date().getSeconds() < 10 ? '0' : '' }}{{ new Date().getSeconds() }} </div>
                </div>
                <div class="comments">
                    <p class="stream-desk-name">Общий чат</p>
                    <div class="comments-area">
                        <div class="comments-users"></div>
                        <div class="comments-layer">
                            <div class="comments-post">
                                <input type="text" placeholder="Пишите здесь" class="comments-post-input">
                                <button class="comments-post-button">
                                    <img src="/assets/send.svg" class="comments-post-button-icon" alt="">
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
</template>

<script lang="ts" setup>
import StreamComponent from '../../components/StreamComponent.vue'

</script>

<style scoped lang="scss"></style>