<script>
	export let name = 'Joe Shmoe';
	export let title = 'Software Engineer';
</script>

<header class="grid grid-cols-2">
	<h1>
		{name}
	</h1>
	<h2>
		{title}
	</h2>
</header>

<style>
	header {
		background-color: var(--bg);
	}

	h1 {
		color: white;
	}
</style>
