<script lang="ts" setup>

</script>

<template>
    <div class="streaming">
        <div class="switchers">
            <div class="switcher">
                <img src="../assets/youtube.svg" alt="" class="">
            </div>
            <div class="switcher kick">
                <img src="../assets/kick.svg" alt="" class="">
                <p class="switcher-name">KICK</p>
            </div>
        </div>
        <div class="frames">
            <div class="frame" id="frame-1">
                <iframe width="100%" height="680" src="https://www.youtube.com/embed/ch7pViSCPd8?si=1bMEzKKK5oXqecVL"
                    title="YouTube video player" frameborder="0" autoplay="true"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                    referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
            <div class="frame" id="frame-2">
                <iframe width="100%" height="680" src="https://www.youtube.com/embed/ch7pViSCPd8?si=1bMEzKKK5oXqecVL"
                    title="YouTube video player" frameborder="0" autoplay="true"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                    referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
        </div>
    </div>
</template>
