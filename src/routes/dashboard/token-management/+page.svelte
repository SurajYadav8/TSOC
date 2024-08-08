<script>
    let tokens = [
        { name: 'Token 1', symbol: 'TK1', supply: 1000 },
        { name: 'Token 2', symbol: 'TK2', supply: 2000 }
    ];
</script>

<main>
    <h1>Manage Your Tokens</h1>
    <ul>
        {#each tokens as token}
            <li>
                <h2>{token.name} ({token.symbol})</h2>
                <p>Supply: {token.supply}</p>
                <button on:click={() => console.log('Distribute Tokens')}>Distribute Tokens</button>
                <button on:click={() => console.log('View Transactions')}>View Transactions</button>
            </li>
        {/each}
    </ul>
</main>
