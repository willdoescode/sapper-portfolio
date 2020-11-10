<script>
	import Nav from "../components/Nav.svelte";

	export let segment;
</script>

<style>
	:global(body) {
		width: 100%;
		height: 100%;
		background-color: #181123;
		background-size: contain;
	}
</style>

<Nav {segment} />

<main>
	<slot />
</main>
