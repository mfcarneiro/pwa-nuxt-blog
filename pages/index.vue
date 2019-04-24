<template>
	<div>
		<v-list v-for="post in postPreview" :key="post.id">
			<PostPreview
				:id="post.id"
				:title="post.title"
				:preview-text="post.previewText"
				:thumbnail="post.thumbnail"
			/>
		</v-list>
	</div>
</template>

<script>
const PostPreview = () => import('~/components/posts/PostPreview');

export default {
	components: {
		PostPreview,
	},

	data() {
		return {
			postPreview: [
				{
					id: '1',
					title: 'Kangaroo Valley Safari',
					previewText:
						'Lorem ipsum dolor sit amet, brute iriure accusata ne mea. Eos suavitate referrentur ad, te duo agam libris qualisque, utroque quaestio accommodare no qui. Et percipit laboramus usu, no invidunt verterem nominati mel. Dolorem ancillae an mei, ut putant invenire splendide mel, ea nec propriae adipisci. Ignota salutandi accusamus in sed, et per malis fuisset, qui id ludus appareat.',
					thumbnail: 'https://cdn.vuetifyjs.com/images/cards/desert.jpg',
				},
				{
					id: '2',
					title: 'Suricato Valley Safari',
					previewText:
						'Lorem ipsum dolor sit amet, brute iriure accusata ne mea. Eos suavitate referrentur ad, te duo agam libris qualisque, utroque quaestio accommodare no qui. Et percipit laboramus usu, no invidunt verterem nominati mel. Dolorem ancillae an mei, ut putant invenire splendide mel, ea nec propriae adipisci. Ignota salutandi accusamus in sed, et per malis fuisset, qui id ludus appareat.',
					thumbnail: 'https://cdn.vuetifyjs.com/images/cards/desert.jpg',
				},
			],
		};
	},
};
</script>

<style lang="scss" scoped></style>
