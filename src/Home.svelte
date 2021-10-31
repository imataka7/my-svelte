<script>
  import { Link } from 'svelte-routing';
	export let name = 'HOST3';
</script>

<h1>Hello {name}!</h1>
<Link to="about">About</Link>
<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>

<style>
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
</style>