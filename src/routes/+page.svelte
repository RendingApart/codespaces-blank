<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<script lang="ts">
	import { writable } from "svelte/store";

  let count = writable(0);
</script>

<button on:click={() => {
  $count++
}}>{$count}</button>