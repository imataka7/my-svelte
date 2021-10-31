<script>
  import { link } from 'svelte-spa-router';
</script>

<h1>This is a about page</h1>
<a href="/" use:link>Home</a>

<style>
	h1 {
		color: #ff3e00;
		/* text-transform: uppercase; */
		font-size: 4em;
		font-weight: 100;
	}
</style>