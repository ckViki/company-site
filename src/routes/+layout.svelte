<script>
	import '../app.css';
	let { children } = $props();
</script>

<div class="app bg-black">
	<main>
		{@render children()}
	</main>
</div>

<style>
</style>
