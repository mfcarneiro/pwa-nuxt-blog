<template>
	<v-toolbar dark color="primary">
		<v-toolbar-side-icon></v-toolbar-side-icon>

		<v-toolbar-title class="white--text"
			>The Developers Corner</v-toolbar-title
		>

		<v-spacer></v-spacer>

		<v-btn icon nuxt to="/posts">
			<v-icon>mdi-file-document-box-multiple-outline</v-icon>
		</v-btn>

		<v-btn icon nuxt to="admin/new-post">
			<v-icon>mdi-pencil-circle-outline</v-icon>
		</v-btn>

		<v-btn icon nuxt to="/login">
			<v-icon>mdi-account-circle</v-icon>
		</v-btn>
	</v-toolbar>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
