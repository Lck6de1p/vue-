<template>
    <li class="ck-swiper-item" :style="{width: width + 'px'}">
        <slot></slot>
    </li>
</template>

<script>
export default {
    data() {
        return {
            width: ''
        }
    },
    mounted() {
        this.width = document.querySelector('.ck-swiper').clientWidth;
    }
}
</script>

<style lang="scss" scoped>
.ck-swiper-item {
    height: 100%;
    flex-shrink: 0;
    img {
        width: 100%;
        height: 100%;
    }
}
</style>