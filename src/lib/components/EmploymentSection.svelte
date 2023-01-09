<script>
	export let employer = '';
	export let title = '';
	export let location = '';
	export let start = '';
	export let end = '';
	export let description = '';
</script>

<h2 class="text-2xl font-bold">{employer}</h2>
<h3 class="text-xl font-bold">{title}</h3>
<h4 class="text-lg font-bold">{location}</h4>
<h5 class="text-lg font-bold">{start} - {end}</h5>
<p class="text-lg">{description}</p>
