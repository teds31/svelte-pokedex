<script>
	import '../app.postcss';
	import Nav from '$lib/nav.svelte';
</script>

<Nav />
<div class="p-8 max-w-6xl mx-auto">
	<slot />
</div>
