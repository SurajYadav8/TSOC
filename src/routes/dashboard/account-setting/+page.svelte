<script>
    let email = 'user@example.com';
    let password = '********';
</script>

<main>
    <h1>Account Settings</h1>
    <form on:submit|preventDefault={() => console.log('Account Updated')}>
        <label>
            Email
            <input type="email" bind:value={email} placeholder="Enter your email" />
        </label>
        <label>
            Password
            <input type="password" bind:value={password} placeholder="Enter your password" />
        </label>
        <button type="submit">Update</button>
    </form>
</main>
