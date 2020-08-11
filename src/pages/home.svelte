<script>

    import Charitylist from "../components/Charitylist.svelte";
    
    let title = "Charity";
    let charities = ['Charity 1','Charity 2','Charity 3'];
    </script>
    
    <style>
        h1 {
            font-size: 3em;
            color:brown;
            }
    </style>
    <svelte:head>
        href="https://cdn.rawgit.com/kimeiga/bahunya/css/bahunya-0.1.3.css"
        rel="stylesheet "
    </svelte:head>
    <div>
    <h1>{title}</h1>
    <Charitylist {charities}/>
    </div>
    