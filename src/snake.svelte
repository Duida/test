<script>
	export let name;
	
</script>
<svelte:options tag="svelte-snake" immutable={true} />
<main>
	<h1>Hello Duida!</h1>
	<button>Click</button>
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