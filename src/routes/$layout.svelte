<script>
  import Nav from '$components/Nav';



</script>

<main>
  <Nav />
  <slot />
</main>

<style lang='scss'>


	main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

</style>