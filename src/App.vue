<template>
	<div id="nav">
		<router-link to="/">Home</router-link>
		<router-link to="/about">About</router-link>
		<router-link to="/brazil">Brazil</router-link>
	</div>

	<div class="container">
		<router-view></router-view>
	</div>
</template>

<script>
import { RouterLink, RouterView } from "vue-router";

export default {
	components: {
		RouterLink,
		RouterView,
	},
};
</script>
