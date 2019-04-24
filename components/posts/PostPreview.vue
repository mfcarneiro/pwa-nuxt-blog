<script>
export default {
	props: {
		id: {
			type: String,
			required: true,
		},
		title: {
			type: String,
			required: true,
		},
		previewText: {
			type: String,
			required: true,
		},
		thumbnail: {
			type: String,
			required: true,
		},
	},
};
</script>

<template>
	<div>
		<v-flex xs12 sm6 offset-sm3>
			<v-card>
				<v-img :src="thumbnail" aspect-ratio="2.75"></v-img>

				<v-card-title primary-title>
					<div>
						<h3 class="headline mb-0">{{ title }}</h3>
						<div>{{ previewText }}</div>
					</div>
				</v-card-title>
				<v-card-actions>
					<v-btn flat color="blue-gray" nuxt :to="`/posts/${id}`">
						Open post
					</v-btn>
					<v-btn flat color="blue-gray">Explore</v-btn>
				</v-card-actions>
			</v-card>
		</v-flex>
	</div>
</template>
