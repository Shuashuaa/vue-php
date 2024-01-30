<template>
	<main>
		<MainPage />
	</main>
</template>

<script>
import { defineComponent } from 'vue';
import MainPage from '../components/MainPage.vue'

export default defineComponent({
	components: {
		MainPage,
	},

	// setup() {
	// }
});
</script>

<style>
	html {
		scroll-behavior: smooth;
	}
</style>