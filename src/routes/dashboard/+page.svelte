<script>
    // Import any necessary stores or scripts
</script>

<main>
    <div class="dashboard-container">
        <h1>Dashboard</h1>
        <p>Welcome to your dashboard! Here you can manage your tokens and account settings.</p>
        <nav>
            <ul>
                <li><a href="/dashboard/token-creation">Token Creation</a></li>
                <li><a href="/dashboard/token-management">Token Management</a></li>
                <li><a href="/dashboard/account-settings">Account Settings</a></li>
                <li><a href="/logout">Logout</a></li>
                <li><a href="/">Back</a></li>
            </ul>
        </nav>
    </div>
</main>

<style>
    /* Apply background image to the entire page */
    main {
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh; /* Full viewport height */
        background-image: url('https://images.unsplash.com/photo-1597832270917-379d08707a26?fit=crop&w=1500&h=1000'); /* Use a reliable image URL */
        background-size: cover; /* Cover the entire viewport */
        background-position: center; /* Center the image */
        background-repeat: no-repeat; /* Prevent repeating */
        padding: 2rem;
        background-color: #f9f9f9; /* Fallback color */
    }

    .dashboard-container {
        background: rgba(255, 255, 255, 0.9); /* White background with slight transparency */
        border-radius: 0.75rem; /* Rounded corners */
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1); /* Slightly larger shadow for depth */
        padding: 3rem; /* Increased padding for more space */
        max-width: 700px; /* Larger maximum width for the container */
        width: 100%; /* Full width within max-width */
        box-sizing: border-box; /* Include padding in the element's width */
        text-align: center;
    }

    h1 {
        font-size: 3rem; /* Larger font size for the heading */
        color: #333; /* Darker color for better readability */
        margin-bottom: 2rem; /* Increased spacing below the heading */
    }

    p {
        font-size: 1.5rem; /* Larger font size for paragraph text */
        line-height: 1.6; /* Improved line height for readability */
        margin-bottom: 2.5rem; /* Increased spacing below the paragraph */
        color: #555; /* Dark gray color for the text */
    }

    nav ul {
        list-style: none;
        padding: 0;
        margin: 0;
    }

    nav ul li {
        margin: 1.5rem 0; /* Increased spacing between navigation items */
    }

    nav a {
        text-decoration: none;
        color: #007bff; /* Primary color for links */
        font-size: 1.5rem; /* Larger font size for links */
        font-weight: 500; /* Slightly bold text for emphasis */
        padding: 0.75rem 1.5rem; /* Increased padding for a bigger clickable area */
        border-radius: 0.25rem; /* Rounded corners for the links */
        transition: background-color 0.3s ease, color 0.3s ease; /* Smooth transition for hover effect */
    }

    nav a:hover {
        background-color: #f1f1f1; /* Light background color on hover */
        color: #0056b3; /* Darker color on hover */
        text-decoration: underline; /* Underline on hover for better visibility */
    }
</style>
