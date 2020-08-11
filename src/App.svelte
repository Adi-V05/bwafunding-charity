<script>

import Charitylist from './Charitylist.svelte';

let tittle = "charity";
setTimeout (function () {
	tittle = "Donation";
}, 2000) ;
</script>

<style>
h1 {
	font-size: 3em;
	color: brown;
}
:global(div) {
	border: 0.5em solid green;
    padding: 1em;
}
</style>
<div>
	<h1>{tittle}</h1>
	<Charitylist/>
</div>