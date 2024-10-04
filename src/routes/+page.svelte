<script lang="ts">
	import Component from './Component.svelte';
</script>

<!-- @utility can be overridden -->
<p class="flex justify-center gap-4 pt-20">
	<Component class="btn-sm"></Component>
	<Component class="btn-sm rounded-none"></Component>
</p>

<article class="prose mx-auto">
	<!-- Default red text -->
	<p>I'm red</p>

	<!-- Can be overridden when importing prose in plugins layer -->
	<p class="text-blue-500">If I'm blue it's working</p>
</article>
