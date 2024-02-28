<script>
	import Contact from '../../components/Contact.svelte';
</script>

<svelte:head>
	<title>Contact - Svelte + Tailwind Template</title>
	<meta name="description" content="Contact this app" />
</svelte:head>

<div class="w-full h-screen">
	<div class="text-center font-semibold">
		<h1 class="text-5xl mt-16">
			<span class="text-blue-700 tracking-wide">Contact </span>
			<span>Pages</span>
		</h1>
		<p class="pt-6 text-xl text-gray-400 font-normal w-full px-8 md:w-full">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit.
		</p>
	</div>
	<Contact />
</div>
