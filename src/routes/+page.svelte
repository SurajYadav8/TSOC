<script>
    import { page } from '$app/stores';
</script>

<nav>
    <div class="nav-content">
        <img src="https://miro.medium.com/v2/resize:fit:913/1*LUZ1SIjlpuu2A78w-enPAw.jpeg" alt="Real Estate Website" class="nav-image"/>
        <h1 class="nav-title">Real Estate Website</h1>
    </div>
    <ul>
        <li><a href="/home">Home</a></li>
        <li><a href="/login">Login</a></li>
        <li><a href="/register">Register</a></li>
        <li><a href="/dashboard">Dashboard</a></li>
    </ul>
</nav>

<main>
    <slot></slot>
</main>

<style>
    /* Full-width navigation bar */
    nav {
        text-align: center;
        background-color: #ffffff; /* White background for a clean look */
        padding: 2rem 4rem; /* Increased padding for more space */
        border-bottom: 2px solid #e0e0e0; /* Slightly thicker border */
        width: 100%; /* Full width */
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Deeper shadow for more emphasis */
        box-sizing: border-box; /* Include padding and border in the element's total width and height */
    }

    .nav-content {
        margin-bottom: 2rem; /* Increased spacing for more separation */
    }

    .nav-image {
        width: 100%; /* Full width of the container */
        max-width: 1000px; /* Doubled maximum width for the image */
        height: auto;
        border-radius: 1rem; /* Larger border radius for a more prominent look */
        border: 4px solid #e0e0e0; /* Thicker border around the image */
    }

    .nav-title {
        font-size: 3.6rem; /* Doubled font size for the title */
        font-weight: 600; /* Bold text */
        margin: 1rem 0; /* Increased margin for spacing */
        color: #333; /* Darker color for better readability */
    }

    nav ul {
        list-style: none;
        padding: 0;
        margin: 0;
        display: flex;
        justify-content: center; /* Center the links horizontally */
        gap: 3rem; /* Increased space between navigation items */
    }

    nav ul li {
        margin: 0;
    }

    nav ul li a {
        text-decoration: none;
        color: #007bff; /* Primary color for links */
        font-size: 2rem; /* Doubled font size for links */
        padding: 1rem 2rem; /* Increased padding for clickable area */
        border-radius: 0.5rem; /* Larger border radius for the links */
        transition: background-color 0.3s ease, color 0.3s ease; /* Smooth transition for hover effect */
    }

    nav ul li a:hover {
        background-color: #f1f1f1; /* Subtle background color on hover */
        color: #0056b3; /* Darker color on hover for better contrast */
    }

    main {
        background-image: url('https://assets.everspringpartners.com/fe/06/f23661be455e97d009c6ae418995/real-estate-finance.jpg'); /* Background image */
        background-size: cover; /* Cover the entire viewport */
        background-position: center; /* Center the image */
        background-repeat: no-repeat; /* Prevent repeating */
        padding: 4rem; /* Increased padding for more space */
        color: #ffffff; /* White text color for contrast */
        min-height: 100vh; /* Full viewport height */
        box-sizing: border-box; /* Include padding in the element's width */
        text-align: center;
    }

    .nav-content, .nav-title, nav ul, nav ul li a {
        z-index: 1; /* Ensure navigation content is above the background image */
    }

    .nav-image {
        z-index: 1; /* Ensure the image is also above the background */
    }
</style>
