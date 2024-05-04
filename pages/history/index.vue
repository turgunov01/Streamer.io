<template>
    <div class="history">
        <h1 class="history-title">Прошлые стримы</h1>
        <p class="history-description">статистика за прошлые стримы </p>

        <div class="history-content">
            <div class="history-statistics">
                <div class="history-cards">
                    <div class="history-card">
                        <div class="history-card-icon"></div>
                        <div class="history-card-params">
                            <p class="history-card-name">СЫГРАННО СЛОТОВ</p>
                            <p class="history-card-count">20</p>
                        </div>
                    </div>
                    <div class="history-card">
                        <div class="history-card-icon"></div>
                        <div class="history-card-params">
                            <p class="history-card-name">САМЫЙ БОЛЬШОЙ ВЫИГРЫШ</p>
                            <p class="history-card-count">600.000р</p>
                        </div>
                    </div>
                    <div class="history-card">
                        <div class="history-card-icon"></div>
                        <div class="history-card-params">
                            <p class="history-card-name">КОЛИЧЕСТВО СТРИМОВ</p>
                            <p class="history-card-count">42</p>
                        </div>
                    </div>
                    <div class="history-card">
                        <div class="history-card-icon"></div>
                        <div class="history-card-params">
                            <p class="history-card-name">КОЛИЧЕСТВО ДЕПОЗИТОВ</p>
                            <p class="history-card-count">5</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="history-blank">
                <h1 class="history-blank-name">Стримы</h1>
                <div class="history-videos">
                    <div class="history-video">
                        <img src="/assets/stream-item.jpg" class="history-video-content" alt="">
                        <div class="history-video-info">
                            <div class="history-video-info-params">
                                <h4 class="history-video-slot"><span>Слот</span>: Arabika play</h4>
                                <p class="history-video-win"><span>Чистый выигрыш</span>: 100 000р</p>
                                <p class="history-video-bet"><span>Ставка</span>: 1000Р</p>
                            </div>
                            <p class="history-video-date">Дата: {{ date.day < 10 ? '0' : '' }}{{ date.day }}.{{ date.month < 10 ? '0' : '' }}{{
                                date.month }}.{{ date.year }}</p>
                        </div>
                    </div>
                    <div class="history-video">
                        <img src="/assets/stream-item.jpg" class="history-video-content" alt="">
                        <div class="history-video-info">
                            <div class="history-video-info-params">
                                <h4 class="history-video-slot"><span>Слот</span>: Arabika play</h4>
                                <p class="history-video-win"><span>Чистый выигрыш</span>: 100 000р</p>
                                <p class="history-video-bet"><span>Ставка</span>: 1000Р</p>
                            </div>
                            <p class="history-video-date">Дата: {{ date.day < 10 ? '0' : '' }}{{ date.day }}.{{ date.month < 10 ? '0' : '' }}{{
                                date.month }}.{{ date.year }}</p>
                        </div>
                    </div>
                    <div class="history-video">
                        <img src="/assets/stream-item.jpg" class="history-video-content" alt="">
                        <div class="history-video-info">
                            <div class="history-video-info-params">
                                <h4 class="history-video-slot"><span>Слот</span>: Arabika play</h4>
                                <p class="history-video-win"><span>Чистый выигрыш</span>: 100 000р</p>
                                <p class="history-video-bet"><span>Ставка</span>: 1000Р</p>
                            </div>
                            <p class="history-video-date">Дата: {{ date.day < 10 ? '0' : '' }}{{ date.day }}.{{ date.month < 10 ? '0' : '' }}{{
                                date.month }}.{{ date.year }}</p>
                        </div>
                    </div>
                    <div class="history-video">
                        <img src="/assets/stream-item.jpg" class="history-video-content" alt="">
                        <div class="history-video-info">
                            <div class="history-video-info-params">
                                <h4 class="history-video-slot"><span>Слот</span>: Arabika play</h4>
                                <p class="history-video-win"><span>Чистый выигрыш</span>: 100 000р</p>
                                <p class="history-video-bet"><span>Ставка</span>: 1000Р</p>
                            </div>
                            <p class="history-video-date">Дата: {{ date.day < 10 ? '0' : '' }}{{ date.day }}.{{ date.month < 10 ? '0' : '' }}{{
                                date.month }}.{{ date.year }}</p>
                        </div>
                    </div>
                    <div class="history-video">
                        <img src="/assets/stream-item.jpg" class="history-video-content" alt="">
                        <div class="history-video-info">
                            <div class="history-video-info-params">
                                <h4 class="history-video-slot"><span>Слот</span>: Arabika play</h4>
                                <p class="history-video-win"><span>Чистый выигрыш</span>: 100 000р</p>
                                <p class="history-video-bet"><span>Ставка</span>: 1000Р</p>
                            </div>
                            <p class="history-video-date">Дата: {{ date.day < 10 ? '0' : '' }}{{ date.day }}.{{ date.month < 10 ? '0' : '' }}{{
                                date.month }}.{{ date.year }}</p>
                        </div>
                    </div>
                    <div class="history-video">
                        <img src="/assets/stream-item.jpg" class="history-video-content" alt="">
                        <div class="history-video-info">
                            <div class="history-video-info-params">
                                <h4 class="history-video-slot"><span>Слот</span>: Arabika play</h4>
                                <p class="history-video-win"><span>Чистый выигрыш</span>: 100 000р</p>
                                <p class="history-video-bet"><span>Ставка</span>: 1000Р</p>
                            </div>
                            <p class="history-video-date">Дата: {{ date.day < 10 ? '0' : '' }}{{ date.day }}.{{ date.month < 10 ? '0' : '' }}{{
                                date.month }}.{{ date.year }}</p>
                        </div>
                    </div>
                    <div class="history-video">
                        <img src="/assets/stream-item.jpg" class="history-video-content" alt="">
                        <div class="history-video-info">
                            <div class="history-video-info-params">
                                <h4 class="history-video-slot"><span>Слот</span>: Arabika play</h4>
                                <p class="history-video-win"><span>Чистый выигрыш</span>: 100 000р</p>
                                <p class="history-video-bet"><span>Ставка</span>: 1000Р</p>
                            </div>
                            <p class="history-video-date">Дата: {{ date.day < 10 ? '0' : '' }}{{ date.day }}.{{ date.month < 10 ? '0' : '' }}{{
                                date.month }}.{{ date.year }}</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts" setup>

const date = {
    day: new Date().getDate(),
    month: new Date().getMonth(),
    year: new Date().getFullYear()
}

</script>

<style lang="scss" scoped></style>