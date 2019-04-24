<template>
	<v-layout align-center justify-center row fill-height>
		<v-flex xs12 sm6 pa-3>
			<v-card>
				<v-card-title primary-title>
					<div>
						<h3 class="headline mb-0">Welcome back, Nero.</h3>
					</div>
				</v-card-title>

				<v-card-text>
					<v-form>
						<v-layout row>
							<v-flex xs12>
								<v-text-field label="email"></v-text-field>
							</v-flex>
						</v-layout>
						<v-layout row>
							<v-flex xs12>
								<v-text-field label="password"></v-text-field>
							</v-flex>
						</v-layout>
					</v-form>
				</v-card-text>

				<v-card-actions>
					<v-spacer></v-spacer>
					<v-btn flat round color="secondary" nuxt to="/">Back</v-btn>
					<v-btn round color="primary" nuxt to="/admin">Login</v-btn>
				</v-card-actions>
			</v-card>
		</v-flex>
	</v-layout>
</template>

<script>
export default {
	layout: 'loginLayout',
};
</script>

<style scoped>
.background-card-color {
	background-color: #fafafa;
}
</style>
