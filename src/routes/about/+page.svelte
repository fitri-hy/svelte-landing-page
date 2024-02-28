<script>
	import About from '../../components/About.svelte';
</script>

<svelte:head>
	<title>About - Svelte + Tailwind Template</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="w-full h-screen">
	<div class="text-center font-semibold">
		<h1 class="text-5xl mt-16">
			<span class="text-blue-700 tracking-wide">About </span>
			<span>Pages</span>
		</h1>
		<p class="pt-6 text-xl text-gray-400 font-normal w-full px-8 md:w-full">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit.
		</p>
	</div>
	<About />
</div>
