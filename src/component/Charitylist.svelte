<script>
    export let charities;
</script>
<div>
    <h2>Daftar Charity</h2>
    {#if charities !==undefined}
        
     <pre>{charities}</pre>
<ul>
    <li>Daftar 1</li>
    <li>Daftar 2</li>
</ul>
{/if}
</div>
