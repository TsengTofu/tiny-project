<script>
	import Navbar from './Layout/Navbar.svelte';
	let name = 'Tofu Tseng';
</script>

<main>
	<h1>Hello {name}!</h1>
	<Navbar></Navbar>
</main>

<style>
	main {
		text-align: center;
		max-width: 240px;
	}

	h1 {
		color: #4958ad;
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