<script>
	import { onDestroy, onMount } from 'svelte';
	onMount(() => console.log('Mounted posts page'));
	onDestroy(() => console.log('Unmounted posts page'));
</script>

<nav>
	<ul>
		<li><a href="/">Home</a></li>
		<li><a href="/posts">Posts</a></li>
	</ul>
</nav>

<h1>Post Page</h1>

<style>
	h1 {
		color: #a13434;
	}
</style>
