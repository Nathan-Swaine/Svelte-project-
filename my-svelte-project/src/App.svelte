<script>
	let name ="Nathan ran down the road and turned left"
</script>

<main>
	<h1> Svelte</h1>
	<p> Welcome to Nathan's first Svelte project. Hopefully it goes well.</p>
	<p> This is what Nathan just did! {name}</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>