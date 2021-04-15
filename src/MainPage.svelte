<script>
	import Button from "./Button.svelte";

	function loginClicked() {
		document.location.href = "login";
	}
</script>

<h1 class="title">
	Superlytics
</h1>
<main>
	<p>Are you sick and tired of a slow, giant, tracker infested analytics service? AHEM GOOGLE ANALYTICS.</p>
	<p>You just wanna know who is visiting your site, if you have visitors at all. Boom Superlytics, it exists, and it just works.</p>
</main>

<Button Value="Login" clickfunction={loginClicked} on:click={loginClicked} />

<style>
	.title {
		text-align: center;
		margin: 0;
		padding-top: 20px;
	}

	main {
		margin: 0 auto;
		font-size: 1rem;
		width: clamp(45ch, 50%, 75ch);
	}


</style>