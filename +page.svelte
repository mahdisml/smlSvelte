<script>
	import {Store} from '../store.svelte'
	import Child from './child.svelte';
	let store = new Store()

</script>

<button on:click={() => store.count++}>
	clicks: {store.count}
</button>
<Child store="{store}"/>
