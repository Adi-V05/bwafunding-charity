<script>

    import Charitylist from "../component/Charitylist.svelte";
    
    let tittle = "charity";
    let charities = ['Charity 1','Charity 2', 'Charity 3'];
    </script>
    
    <style>
    h1 {
        font-size: 3em;
        color: brown;
    }
    </style>
    <div>
        <h1>{tittle}</h1>
        <Charitylist charities = {charities}/>
        <Charitylist />
    </div>