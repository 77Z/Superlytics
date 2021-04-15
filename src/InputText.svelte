<script>
	import { createEventDispatcher } from 'svelte';
	let dispatch = createEventDispatcher();
	//see https://www.youtube.com/watch?v=yCkYm4zze8I

	//PUBLIC VARIABLES
	export let Placeholder = "...";
	export let Value       = "";
	export let Password    = false;


</script>

<input type={Password === true ? "password" : "text"} placeholder={Placeholder} value={Value}>