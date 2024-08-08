<script>
    import { onMount } from 'svelte';
    import { page } from '$app/stores';

    onMount(() => {
        // Add your authentication check logic here
        // If not authenticated, redirect to login
        // if (!authenticated) {
        //     location.href = '/login';
        // }
    });
</script>

<main>
    <h1>Dashboard</h1>
    <nav>
        <ul>
            <li><a href="/dashboard/token-creation/project-details">Token Creation</a></li>
            <li><a href="/dashboard/token-management">Token Management</a></li>
            <li><a href="/dashboard/account-settings">Account Settings</a></li>
            <li><a href="/dashboard/logout">Logout</a></li>
        </ul>
    </nav>
    <section>
        <slot></slot>
    </section>
</main>

<style>
    nav ul {
        list-style: none;
        padding: 0;
    }
    nav ul li {
        display: inline;
        margin-right: 1rem;
    }
    nav ul li a {
        text-decoration: none;
        color: #007bff;
    }
    nav ul li a:hover {
        text-decoration: underline;
    }
</style>
