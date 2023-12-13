<script>
	let { store } = $props();
</script>

<button on:click={() => store.count++}>
	clicks: {store.count}
</button>
