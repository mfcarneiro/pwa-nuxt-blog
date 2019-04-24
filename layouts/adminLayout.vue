<script>
const NavigationBar = () => import('~/components/navbar/NavigationBar');

export default {
	components: {
		NavigationBar,
	},
};
</script>

<template>
	<v-app>
		<NavigationBar />
		<v-content>
			<Nuxt />
		</v-content>
	</v-app>
</template>
