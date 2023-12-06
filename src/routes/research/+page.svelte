<script>
	import Tile from '../Tile.svelte';
</script>

<main>
<h1>Our research</h1>

<div class="projects">
<Tile />
<Tile />
<Tile />
<Tile />
</div>

Computational biophysics at <a href="https://www.bbk.ac.uk/">Birkbeck, University of London.</a>
</main>

<style>
.projects {
	display: grid;
	grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
	gap: 32px;
}
</style>
