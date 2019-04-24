<script>
export default {};
</script>

<template>
	<section>
		<v-container fluid>
			<v-layout
				align-content-space-around
				justify-space-around
				fill-height
				row
			>
				<v-flex>
					<v-card>
						<v-card-title primary-title>
							<h2 class="headline mb-0">
								New Post!
							</h2>
						</v-card-title>
						<v-container>
							<v-layout justify-center column fill-height>
								<v-flex xs12>
									<v-layout row wrap>
										<v-flex xs12>
											<v-text-field label="Author name">
											</v-text-field>
											<v-text-field label="Title"> </v-text-field>
											<v-text-field label="Thumbnail link">
											</v-text-field>
											<v-textarea
												auto-grow
												no-resize
												label="Content"
											>
											</v-textarea>
										</v-flex>
									</v-layout>
								</v-flex>
							</v-layout>
						</v-container>
						<v-card-actions>
							<v-spacer></v-spacer>
							<v-btn flat round color="red">Cancel</v-btn>
							<v-btn round color="primary">Submit</v-btn>
						</v-card-actions>
					</v-card>
				</v-flex>
			</v-layout>
		</v-container>
	</section>
</template>

<style scoped></style>
