<script lang="ts">
	let { class: className }: { class?: string } = $props();
</script>

<button class={'not-[.allowed]:text-red-500 ' + className}>Hey</button>

<style>
	/* Whether layered or not, defined here or in app.css responsive classes do not work */
	/* @layer components {
		.btn-sm {
			padding: var(--spacing-1);
			background-color: var(--color-indigo-500);
			color: var(--color-gray-700);
		}

		.btn-lg {
			padding: var(--spacing-10);
			background-color: var(--color-red-500);
			color: var(--color-blue-700);
		}
	} */
</style>
