<script lang="ts">
	import Title from '$lib/shared/Title.svelte';

	export let status: string;
	// export let error: Error;
</script>

<Title title={status} />
<div class="flex justify-center items-center h-screen">
	<p>Some thing went wrong!</p>
	<!-- <h1>{status}</h1> -->
	<!-- <p>{error?.message}</p> -->
</div>
