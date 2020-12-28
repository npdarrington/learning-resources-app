<template>
	<li>
		<article>
			<header>
				<h3></h3>
				<button>Delete</button>
			</header>
		</article>
		<p></p>
		<nav>
			<a href="#">View Resource</a>
		</nav>
	</li>
</template>

<script>
export default {
	props: {
		title: { type: String, required: true },
		description: { type: String, required: true },
		link: { type: String, required: true },
	},
};
</script>
