<script>
	import Tile from '../Tile.svelte';
</script>

<main>
<h1>Our research</h1>

<div class="projects">
	<Tile
		title="Understand dynamic ensembles of biomolecular assemblies"
		summary="Use methods that inherently represent ensembles of models."
		details="Projects: Contact prediction,
			Conformational sampling,"
	/>
	<Tile
		title="Cellular-scale molecular dynamics"
		summary="Develop novel methods to tackle large assemblies."
		details="Hierarchical coarse-grain modelling"
	/>
	<Tile
		title="Integrated biophysical modelling: end-to-end representations"
		summary="Integrate representation of biophysical experiment in data modelling."
		details="Flexible fitting for cryo-EM, Mycobacterium cell wall"
	/>
</div>

</main>

<style>
.projects {
	display: grid;
	grid-template-columns: repeat(auto-fill, minmax(600px, 1fr));
	gap: 32px;
}
</style>
