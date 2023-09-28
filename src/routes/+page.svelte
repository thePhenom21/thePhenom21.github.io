<script lang="ts">
	let theme = 'default';
	let days = '1';
	let level = '1';
</script>

<div class="custom_prompt">
	<label> Theme </label>
	<input type="text" bind:value={theme} />
	<label> Days </label>
	<input type="text" bind:value={days} />
	<label> Level </label>
	<input type="text" bind:value={level} />
</div>

<style>
	.custom_prompt {
		display: grid;
	}

	label,
	input {
		grid-column: 1 / 2;
		margin: 5px;
	}
</style>
