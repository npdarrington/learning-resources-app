<template>
	<base-card>
		<form>
			<div class="form-control">
				<label for="title">Title:</label>
				<input type="text" name="title" id="title" />
			</div>
			<div class="form-control">
				<label for="title">Description:</label>
				<textarea id="description" name="description" rows="3"></textarea>
			</div>
			<div class="form-control">
				<label for="link">Link:</label>
				<input type="url" name="link" id="link" />
			</div>
			<div>
				<base-button type="Submit">Add Resource</base-button>
			</div>
		</form>
	</base-card>
</template>
