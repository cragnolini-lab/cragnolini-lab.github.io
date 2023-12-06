<section class="tile">
	<header>
		<h1>
			<slot name="title">
				Title
			</slot>
		</h1>
	</header>
	<slot name="summary">
		A short summary of this tile.
	</slot>
	<footer>
		<slot name="link">
			See more at...
		</slot>
	</footer>
</section>

<style>
.tile {
	//display: flex;
	background-color: rgba(0, 0, 0, 0.1);
	padding: 32px;
	border-radius: 8px;
}
</style>
