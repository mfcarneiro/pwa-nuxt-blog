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

		<v-btn icon nuxt to="/new-post">
			<v-icon>mdi-pencil-circle-outline</v-icon>
		</v-btn>

		<v-btn icon nuxt to="/login">
			<v-icon>mdi-account-circle</v-icon>
		</v-btn>
	</v-toolbar>
	<!-- <v-toolbar color="primary">
		<v-toolbar-side-icon></v-toolbar-side-icon>
		<v-toolbar-title class="white--text"
			>The Developers Corner</v-toolbar-title
		>
		<v-spacer></v-spacer>
		<v-toolbar-items class="hidden-sm-and-down">
			<v-btn icon flat nuxt to="/">
				<v-icon class="white--text" medium
					>mdi-file-document-box-multiple-outline</v-icon
				>
			</v-btn>
			<v-btn icon flat nuxt to="/about">
				<v-icon class="white--text" medium
					>mdi-pencil-circle-outline</v-icon
				>
			</v-btn>
			<v-btn icon flat nuxt to="/login" color="secondary">
				<v-icon class="white--text" medium>mdi-account-circle</v-icon>
			</v-btn>
		</v-toolbar-items>
	</v-toolbar> -->
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
