<script>
	//PUBLIC VARIABLES
	export let Centered = false;
</script>

<h1 class:center={Centered}>
	<slot></slot>
</h1>

<style>
	.center {
		text-align: center;
	}
</style>