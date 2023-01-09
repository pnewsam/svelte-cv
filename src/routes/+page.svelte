<script>
	import EmploymentSection from '$lib/components/EmploymentSection.svelte';
	import PageSection from '$lib/components/PageSection.svelte';
	import Header from '$lib/components/Header.svelte';

	import { employments } from '../data';
</script>

<Header name="Paul Newsam" />

<h2>Objective</h2>
<p>
	I am a software engineer with a passion for building great products. I am looking for a company
	that values its employees and is committed to building a great product.
</p>

<h2>Experience</h2>

<PageSection title="Employment" />

{#each employments as employment}
	<EmploymentSection
		employer={employment.employer}
		title={employment.title}
		location={employment.location}
		start={employment.start}
		end={employment.end}
		description={employment.description}
	/>
{/each}

<h2>Projects</h2>

<h2>Education</h2>
<h3>University of California, Berkeley</h3>
<h4>B.A. Biology & English</h4>
<h5>December 2009</h5>
<p>
	Relevant Coursework: Data Structures, Algorithms, Computer Architecture, Operating Systems,
	Computer Networks, Database Systems, Software Engineering, Artificial Intelligence, Machine
	Learning, Computer Graphics, Computer Security, Cryptography, Computer Vision, Natural Language
	Processing, Programming Languages, Formal Methods, Computer Game Design, Computer Game
	Programming, Computer Game AI, Computer Game Graphics, Computer Game Sound, Computer Game
	Networking, Computer Game Design, Computer Game Programming, Computer Game AI, Computer Game
	Graphics, Computer Game Sound, Computer Game Networking
</p>
