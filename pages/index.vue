<template>
	<div>
		<post-list></post-list>
	</div>
</template>

<script>
const PostList = () => import('~/components/posts/PostList');

export default {
	components: {
		PostList,
	},
};
</script>

<style lang="scss" scoped></style>
