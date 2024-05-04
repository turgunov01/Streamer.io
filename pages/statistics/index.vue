<template>
    <div class="mis">
        <h1 class="mis-title news-title">Статистика</h1>
        <p class="mis-description news-description">Соревнуйтесь в выполнение простых действий и получайте награды</p>
        <div class="mis-blank">
            <div class="mis-buttons">
                <button class="mis-button active">за день</button>
                <button class="mis-button">недельные</button>
                <button class="mis-button">ежемесячные</button>
            </div>
            <div class="mis-content">
                <div class="mis-dropdowns">
                    <div class="mis-dropdown">
                        <div class="mis-dropdown-heading">
                            <p class="mis-dropdown-title">Статистика по СООБЩЕНИЯМ В ЧАТЕ</p>
                            <img src="/assets/sidebar/chevron.svg" alt="">
                        </div>
                    </div>
                    <table class="mis-table">
                        <thead>
                            <tr>
                                <td>#</td>
                                <td class="name">Имя</td>
                                <td class="count">Количество</td>
                            </tr>
                        </thead>
                        <tbody>
                            <tr v-for="(item, index) in missions">
                                <th> {{ index + 1 }} </th>
                                <th> {{ item.name }} </th>
                                <th> {{ item.count }} </th>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="mis-prize">
                    <span class="mis-prize-icon">
                        <img src="/assets/gift.svg" alt="">
                        <p>Награды</p>
                    </span>
                    <ul class="mis-prize-list">
                        <li class="mis-prize-item" v-for="item in 3">
                            <p class="mis-prize-name">{{ item }} место</p>
                            <p class="mis-prize-count"> {{ item * 100 }} <img src="/assets/points.svg" alt=""> </p>
                        </li>
                    </ul>
                    <button class="mis-prize-button">как работает система наград</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue';

const missions = ref([
    {
        name: 'gott',
        count: 2308,
    },
    {
        name: 'nik',
        count: 1800,
    },
    {
        name: 'sarik',
        count: 900
    },
    {
        name: 'gott',
        count: 2308,
    },
    {
        name: 'nik',
        count: 1800,
    },
    {
        name: 'sarik',
        count: 900
    },
    {
        name: 'gott',
        count: 2308,
    },
    {
        name: 'nik',
        count: 1800,
    },
    {
        name: 'sarik',
        count: 900
    },
    {
        name: 'gott',
        count: 2308,
    },
    {
        name: 'nik',
        count: 1800,
    },
    {
        name: 'sarik',
        count: 900
    },
].sort((a, b) => b.count - a.count))

</script>