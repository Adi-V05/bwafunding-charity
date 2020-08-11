<script>
    import CharityList from "../Components/CharityList.svelte";


    let title = "Charity";
    let charities = ['Charity 1','Charity 2','Charity 3'];
</script>

<style>
h1 {
    font-size: 3em;
    color: blue;
}
</style>

<div>
    <h1>{title}</h1>
    <CharityList {charities}/>
</div>

