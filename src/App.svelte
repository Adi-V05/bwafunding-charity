<script>
import CharityList from ".CharityList.svelte";
import Charitylist from "./Charitylist.svelte";

let tittle = "Charity";
setTimeout(function () {
tittle = "Donation";
}, 2000);
</script>

<style>
    h1 {
        font-size: 3em;
        color:brown;
        }
</style>

<h1>{tittle}</h1>
<Charitylist/>

