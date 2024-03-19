<script>
	import Github from './Github.svelte';
	import Link from './Link.svelte';

	export let title = "Title";
	export let summary = "A short summary of this tile.";
	export let details= "";
	export let link = "";
	export let source = "";
</script>

<section class="tile">
	<header>
		<h1>
			{title}
		</h1>
	</header>

	{#if details}
	<details>
		<summary>{summary}</summary>
		<p>{details}</p>
	</details>
	{:else}
		{summary}
	{/if}

	<footer>
		{#if link}
		<a href={link}>
			<Link />
		</a>
		{/if}
		{#if source}
		<a href={source}>
			<Github />
		</a>
		{/if}

	</footer>
</section>

<style>
.tile {
	background-color: rgba(0, 0, 0, 0.1);
	padding: 32px;
	border-radius: 8px;
}
</style>
