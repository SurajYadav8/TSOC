<script>
    let tokenName = '';
    let tokenSymbol = '';
    let totalSupply = '';
    let additionalFeatures = '';
</script>

<main>
    <h1>Define Token Parameters</h1>
    <form on:submit|preventDefault={() => console.log(tokenName, tokenSymbol, totalSupply, additionalFeatures)}>
        <label>
            Token Name
            <input type="text" bind:value={tokenName} placeholder="Token Name" />
        </label>
        <label>
            Token Symbol
            <input type="text" bind:value={tokenSymbol} placeholder="Token Symbol" />
        </label>
        <label>
            Total Supply
            <input type="number" bind:value={totalSupply} placeholder="Total Supply" />
        </label>
        <label>
            Additional Features
            <input type="text" bind:value={additionalFeatures} placeholder="Additional Features (Optional)" />
        </label>
        <button type="submit">Next</button>
    </form>
</main>
