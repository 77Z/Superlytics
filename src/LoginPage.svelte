<script>
	import Text from "./InputText.svelte";
	import Header from "./Header.svelte";

	/* const recieveFormData = function(e) {
		console.log(e.detail);
	}; */
</script>

<Header Centered>Login</Header>

<Text Placeholder="Username..." />
<br>
<Text Password Placeholder="Password..." />
<!-- Password can also be Password={true} -->