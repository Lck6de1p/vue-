<template>
    <div>
		<swiper>
			<swiper-item><img src="@/assets/img/1.jpg" alt=""></swiper-item>
			<swiper-item><img src="@/assets/img/2.jpg" alt=""></swiper-item>
			<swiper-item><img src="@/assets/img/3.jpg" alt=""></swiper-item>
			<swiper-item><img src="@/assets/img/4.jpg" alt=""></swiper-item>
		</swiper>
    </div>
</template>

<script>
import swiper from '@/components/swiper'
import swiperItem from '@/components/swiperItem'

export default {
    components: {
		swiper,
		swiperItem
	}
}
</script>

<style>

</style>