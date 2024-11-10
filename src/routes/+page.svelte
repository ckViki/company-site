<script lang="ts">
	import Home from './home/+page.svelte';
	import About from './about/+page.svelte';
	import Services from './services/+page.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="w-full">
	<!-- <div class="absolute sticky top-5 w-full flex p-5 bg-none">
		<button class="ml-auto  mr-10 flex gap-2 text-[12px] text-green-500 items-center hover:text-white">
			<span class="tracking-[0.3em]">MENU</span><img src="/img/hamburger.png" alt="">
		</button>
	</div> -->
	<Home />
	<About />
	<Services />

</div>