<script>
	import About from '../components/About.svelte';
	import Services from '../components/Services.svelte';
	import Pricing from '../components/Pricing.svelte';
	import Contact from '../components/Contact.svelte';
</script>

<svelte:head>
	<title>Home - Svelte + Tailwind Template</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<About />
	<Services />
	<Pricing />
	<Contact />
</section>