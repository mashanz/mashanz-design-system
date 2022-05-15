<script>
	import LinkCard from '../components/LinkCard.svelte';
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<Header />

<main class="grid grid-cols-1 md:grid-cols-4 p-5 gap-2">
	<LinkCard url="buttons" title="Buttons" />
	<LinkCard url="cards" title="Cards" />
	<LinkCard url="inputs" title="Inputs" />
	<LinkCard url="tags" title="Tags" />
	<LinkCard url="tables" title="Tables" />
	<LinkCard url="typography" title="Typography" />
</main>

<Footer />
