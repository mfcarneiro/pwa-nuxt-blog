<script>
const NavigationBar = () => import('~/components/navbar/NavigationBar');
const Footer = () => import('~/components/footer/Footer');

export default {
	components: {
		NavigationBar,
		Footer,
	},
};
</script>

<template>
	<v-app>
		<NavigationBar />
		<v-content>
			<Nuxt />
		</v-content>
		<Footer />
	</v-app>
</template>
