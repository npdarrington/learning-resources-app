<template>
	<ul>
		<learning-resource
			v-for="resource in resources"
			:key="resource.id"
			:title="resource.title"
			:description="resource.description"
			:link="resource.link"
		></learning-resource>
	</ul>
</template>

<script>
export default {
	props: {
		resources: {
			type: Array,
			required: true,
		},
	},
};
</script>
