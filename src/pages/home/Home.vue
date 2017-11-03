<template>
	<div>
 		<home-header/>
 		<swiper-content/>
 		<Acitivity-view/>
 	</div>
</template>

<script>

import HeaderComponent from "./Header";
import SwiperComponent from "./Swiper";
import ActivityComponent from "./activity";

export default {
	components: {
		"home-header": HeaderComponent,
		"swiper-content": SwiperComponent,
		"Acitivity-view": ActivityComponent
	}
}
</script>

<style>
</style>
