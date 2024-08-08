<script>
    // You can add any necessary script here
</script>

<main>
    <section class="intro">
        <h1>Welcome to the Real Estate Token Creation Platform</h1>
        <p>
            The Time Chain Summer of Code (TSoC) is a program that brings together developers and enthusiasts
            to work on innovative projects during the summer. Our project, assigned by TSoC, focuses on creating
            a real estate token platform that streamlines property transactions and management through tokenization.
        </p>
        <p>
            This platform will help in creating, managing, and trading real estate tokens with ease and efficiency.
            Below are the links to learn more about the Time Chain Summer of Code and our real estate project.
        </p>
        <div class="auth-links">
            <a href="/login" class="auth-button">Login</a>
            <a href="/register" class="auth-button">Register</a>
        </div>
    </section>

    <section class="links">
        <h2>Learn More About TSoC and Our Project</h2>
        <ul>
            <li><a href="https://medium.com/@abhisheknew2023/my-timechain-summer-of-code-adventure-a-journey-of-growth-and-learning-ea0f2a641736" target="_blank">TSoC Overview</a></li>
            <li><a href="/dashboard">Explore the Real Estate Token Project</a></li>
        </ul>
    </section>
</main>

<style>
    /* Apply background image to the entire page */
    main {
        background-image: url('https://imageio.forbes.com/specials-images/imageserve/657b29edf09ae8354c4debba/Real-estate-agents-shake-hands-after-the-signing-of-the-contract-agreement-is/960x0.jpg?height=474&width=711&fit=bounds');
        background-size: cover; /* Cover the entire viewport */
        background-position: center; /* Center the image */
        background-repeat: no-repeat; /* Prevent repeating */
        padding: 2rem;
        text-align: center;
        color: #ffffff; /* White text color for contrast */
        min-height: 100vh; /* Full viewport height */
        box-sizing: border-box; /* Include padding in the element's width */
    }

    .intro, .links {
        background: rgba(0, 0, 0, 0.6); /* Semi-transparent background for readability */
        border-radius: 0.5rem; /* Rounded corners */
        padding: 2rem;
        margin: 1rem auto;
        max-width: 900px; /* Larger maximum width for the sections */
    }

    h1 {
        font-size: 3rem; /* Larger font size for the main heading */
        margin-bottom: 1.5rem;
    }

    h2 {
        font-size: 2.5rem; /* Larger font size for section headings */
        margin-bottom: 1rem;
    }

    p {
        font-size: 1.5rem; /* Larger font size for paragraph text */
        line-height: 1.6; /* Improved line height for readability */
        margin: 0 0 1.5rem;
    }

    .auth-links {
        margin-top: 2rem;
    }

    .auth-button {
        display: inline-block;
        text-decoration: none;
        color: #ffffff; /* White text color */
        background-color: #007bff; /* Primary color for buttons */
        font-size: 1.5rem;
        font-weight: 500; /* Slightly bold text for emphasis */
        padding: 1rem 2rem; /* Padding for the button */
        border-radius: 0.5rem; /* Rounded corners for the button */
        transition: background-color 0.3s ease, color 0.3s ease; /* Smooth transition for hover effect */
        margin: 0.5rem; /* Spacing between buttons */
    }

    .auth-button:hover {
        background-color: #0056b3; /* Darker color on hover */
        color: #ffffff; /* Maintain white text color on hover */
        text-decoration: none;
    }

    .links ul {
        list-style: none;
        padding: 0;
    }

    .links ul li {
        margin: 0.75rem 0; /* Increased spacing between links */
    }

    .links a {
        text-decoration: none;
        color: #00bfff; /* Light blue color for links */
        font-size: 1.5rem;
        font-weight: 500; /* Slightly bold text for emphasis */
        transition: color 0.3s ease; /* Smooth transition for hover effect */
    }

    .links a:hover {
        color: #1e90ff; /* Darker blue on hover */
        text-decoration: underline;
    }
</style>
