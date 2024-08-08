<script>
    let projectDetails = {
        name: 'Sample Project',
        description: 'Sample Description',
        location: 'Sample Location'
    };
    let tokenParameters = {
        name: 'Sample Token',
        symbol: 'STK',
        supply: 1000
    };
</script>

<main>
    <h1>Confirm Token Creation</h1>
    <div>
        <h2>Project Details</h2>
        <p>Name: {projectDetails.name}</p>
        <p>Description: {projectDetails.description}</p>
        <p>Location: {projectDetails.location}</p>
    </div>
    <div>
        <h2>Token Parameters</h2>
        <p>Token Name: {tokenParameters.name}</p>
        <p>Token Symbol: {tokenParameters.symbol}</p>
        <p>Total Supply: {tokenParameters.supply}</p>
    </div>
    <button on:click={() => console.log('Token Created')}>Create Token</button>
</main>
