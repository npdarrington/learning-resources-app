<template>
	<ul>
		<learning-resource
			v-for="resource in storedResources"
			:key="resource.id"
			:title="resource.title"
			:description="resource.description"
			:link="resource.link"
		></learning-resource>
	</ul>
</template>
