<script>
	import Sidebar from "../components/Sidebar.svelte";
  </script>

<style>
	main {
		position: relative;
		max-width: 56em;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>

<svelte:head>
  <title>Josefine Schaefer - Blog</title>
</svelte:head>

<Sidebar />
<main>
	<slot></slot>
</main>