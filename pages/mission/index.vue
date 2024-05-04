<template>
    <div class="points">
        <h1 class="points-title news-title">Статистика</h1>
        <p class="points-description news-description">Соревнуйтесь в выполнение простых действий и получайте награды
        </p>
        <div class="points-blank">
            <div class="points-buttons">
                <button class="points-button active">за день</button>
                <button class="points-button">недельные</button>
                <button class="points-button">ежемесячные</button>
            </div>
            <div class="points-content">
                <table class="points-table">
                    <thead>
                        <tr>
                            <td>#</td>
                            <td class="name">Задание</td>
                            <td class="count">Награда, АКС</td>
                            <td class="count">Статус</td>
                        </tr>
                    </thead>
                    <tbody>
                        <tr v-for="(item, index) in points">
                            <th> {{ index + 1 }} </th>
                            <th> {{ item.name }} </th>
                            <th class="points-input">
                                <p>{{ (item.count / 10) }}</p>
                                <button class="points-button-get" v-if="item.verified">забрать бонус</button>
                            </th>
                            <th v-if="!item.verified">Не выполнено</th>
                            <th v-else>выполнено</th>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
</template>

<script lang="ts" setup>

const points = ref([
    {
        name: 'gott',
        count: 2308,
        verified: Math.random() < 0.5,
    },
    {
        name: 'nik',
        count: 1800,
        verified: Math.random() < 0.5,
    },
    {
        name: 'sarik',
        count: 900,
        verified: Math.random() < 0.5,
    },
    {
        name: 'gott',
        count: 2308,
        verified: Math.random() < 0.5,
    },
    {
        name: 'nik',
        count: 1800,
        verified: Math.random() < 0.5,
    },
    {
        name: 'sarik',
        count: 900,
        verified: Math.random() < 0.5,
    },
    {
        name: 'gott',
        count: 2308,
        verified: Math.random() < 0.5,
    },
    {
        name: 'nik',
        count: 1800,
        verified: Math.random() < 0.5,
    },
    {
        name: 'sarik',
        count: 900,
        verified: Math.random() < 0.5,
    },
    {
        name: 'gott',
        count: 2308,
        verified: Math.random() < 0.5,
    },
    {
        name: 'nik',
        count: 1800,
        verified: Math.random() < 0.5,
    },
    {
        name: 'sarik',
        count: 900,
        verified: Math.random() < 0.5,
    },
].sort((a, b) => b.count - a.count))


</script>

<style scoped lang="scss"></style>