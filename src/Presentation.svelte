<script>
	import Title			from './slides/Title.svelte';
	import Love				from './slides/examples/Love.svelte';
	import GettingStarted	from './slides/examples/GettingStarted.svelte';

	const partner = ['Svelte', 'Reveal.js'];
</script>

<Title/>
<Love {partner}/>
<GettingStarted/>
