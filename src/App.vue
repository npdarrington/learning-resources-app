<template>
	<ul></ul>
</template>

<script>
import LearningResource from './components/learning-resources/LearningResource';

export default {
	components: {
		LearningResource,
	},
	data() {
		return {
			storedResouces: [
				{
					id: 'official-guide',
					title: 'Official Guide',
					description: 'The official Vue.js documentation',
					link: 'https://vuejs.org',
				},
				{
					id: 'google',
					title: 'Google',
					description: 'Learn to Google',
					link: 'https://google.com',
				},
			],
		};
	},
};
</script>

<style></style>
