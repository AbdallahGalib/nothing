<script>
	export let name;
</script>

<main>
	<h1>Hello Fellow {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 350px;
		margin: 0 auto;
	}

	h1 {
		color: black;
		text-transform: uppercase,lowercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: 1028px;
		}
	}
</style>