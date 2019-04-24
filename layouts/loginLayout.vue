<template>
	<v-app>
		<v-content>
			<Nuxt />
		</v-content>
		<v-footer height="auto" class="background-copyright-footer">
			<v-card class="flex">
				<v-card-actions class="justify-center">
					&copy; {{ new Date().getFullYear() }} —
					<strong>The Developers Corner</strong>
				</v-card-actions>
			</v-card>
		</v-footer>
	</v-app>
</template>

<script>
export default {};
</script>

<style scoped>
.background-copyright-footer {
	background-color: #fafafa;
}
</style>
