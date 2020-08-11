<script>
    import CharityList from "./CharityList.svelte";


    let title = "Charity";
    setTimeout(function (){
        title = "Donation";
    }, 2000);

    let charities = ['Charity 1','Charity 2','Charity 3'];
</script>

<style>
h1 {
    font-size: 3em;
    color: blue;
}
:global(div) {
    border: 0.5em solid blueviolet;
    padding: 1em;
}
</style>

<div>
    <h1>{title}</h1>
    <CharityList charities = {charities}/>
</div>

