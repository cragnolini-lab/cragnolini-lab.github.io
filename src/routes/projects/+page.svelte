<script>
	import Tile from '../Tile.svelte';
</script>

<main>
<h1>Our projects</h1>

<div class="projects">
	<Tile
		title="Contact prediction with deep learning in flexible proteins"
		summary="We build models to predict contact between distant sites in proteins."
		source="https://github.com/namagno/contact-prediction"
	/>
	<Tile
		title="Hierarchical coarse-grain modelling"
		summary="
We investigate how coarse-grain mappings at different resolutions relate to one another and run simulations on biomolecular systems using those simplified models. 
We use graph representations and graph neural networks to automate the coarse-graining of proteins at varying levels of description
and run molecular dynamics simulations using these simplified models with the aim of striking a balance between accuracy and computational cost."
	/>
	<Tile
		title="Conformational sampling of protein structure prediction"
		summary="We develop statistical models to improve the sampling of alternative conformational states in protein structure prediction pipelines."
	/>
	<Tile
		title="Flexible fitting for cryo-EM"
		summary="We develop statistical models to represent the relation between structural variations in biomolecular complexes and the observed cryo-EM density."
	/>
	<Tile
		title="Mycobacterium cell wall"
		summary="Mycobacterial envelopes are complex, with several layers: an internal membrane with a usual phospholipid bilayer, proteins and glycans; a cell wall is present further out, comprised of several layers itself, composed of peptidoglycans, galactans, and mycolic acids, which are long chain fatty acids. The overall structure and arrangements of this envelope have yet to be fully elucidated. Due to the seriousness of mycobacterial infections, developing efficient treatments is a crucial healthcare challenge.
We are developing and refining a full-atom model of this cell wall, based on existing data regarding its structure and composition, and previous reconstruction. Subsequently, the model will be used in molecular dynamics simulations, initially to gauge the model's stability, and with the goal of providing a system to be used for simulating the permeation of organic compounds through this membrane."
	/>
</div>

</main>

<style>
.projects {
	display: grid;
	grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
	gap: 32px;
}
</style>
