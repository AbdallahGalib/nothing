<script>
	let name = 'some thing', age = 20
</script>

<main>
	<input bind:value = {name} />
	<input bind:value = {age} />
	my name is {name} my age is {age}
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 350px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: 1028px;
		}
	}
</style>