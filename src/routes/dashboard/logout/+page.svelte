<script>
    import { onMount } from 'svelte';

    onMount(() => {
        // Add your logout logic here
        // Clear tokens, session, etc.
        // Redirect to login or home page
        location.href = '/login';
    });
</script>

<main>
    <h1>Logging out...</h1>
</main>
