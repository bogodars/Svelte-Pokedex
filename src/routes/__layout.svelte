<script>
	import Nav from '../components/nav.svelte';
</script>

<div class="p-8 max-w-6xl mx-auto">
	<Nav />
</div>
<slot />

<style>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>
