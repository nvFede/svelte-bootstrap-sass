<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial" class="btn btn-danger">Svelte </a>to learn how to build Svelte apps.</p>

	

</main>

<style lang="scss">
	
	@import '../node_modules/bootstrap-sass/assets/stylesheets/_bootstrap.scss';

	$main-color : #115271;

	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: $main-color;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}


</style>