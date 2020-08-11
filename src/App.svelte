<script>

import Charitylist from './Charitylist.svelte';

let tittle = "charity";
setTimeout (function () {
	tittle = "Donation";
}, 2000) ;

let charities = ['Charity 1','Charity 2', 'Charity3'];
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
	<Charitylist charities = {charities}/>
</div>