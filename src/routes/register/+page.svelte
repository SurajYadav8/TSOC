<script>
    let email = '';
    let password = '';
    let confirmPassword = '';
</script>

<main>
    <div class="form-container">
        <h1>Create Your Account</h1>
        <form on:submit|preventDefault={() => console.log(email, password, confirmPassword)}>
            <label>
                Email
                <input type="email" bind:value={email} placeholder="Enter your email" />
            </label>
            <label>
                Password
                <input type="password" bind:value={password} placeholder="Create a password" />
            </label>
            <label>
                Confirm Password
                <input type="password" bind:value={confirmPassword} placeholder="Confirm your password" />
            </label>
            <button type="submit">Register</button>
        </form>
        <footer>
            Already have an account? <a href="/login">Login here</a>
        </footer>
    </div>
</main>

<style>
    main {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh; /* Full viewport height */
        padding: 2rem;
        background-color: #f9f9f9; /* Light background color for the page */
    }

    .form-container {
        background: #ffffff; /* White background for the form container */
        border-radius: 0.75rem; /* Rounded corners */
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
        padding: 2rem;
        max-width: 500px; /* Maximum width for the form */
        width: 100%; /* Full width within max-width */
        box-sizing: border-box; /* Include padding in the element's width */
    }

    h1 {
        font-size: 2.5rem; /* Larger font size for the heading */
        margin-bottom: 1.5rem; /* Spacing below the heading */
        color: #333; /* Darker color for better readability */
        text-align: center; /* Center align the heading */
    }

    form {
        display: flex;
        flex-direction: column;
        gap: 1.5rem; /* Space between form elements */
    }

    label {
        display: flex;
        flex-direction: column;
        font-size: 1.2rem; /* Larger font size for labels */
    }

    input {
        padding: 0.75rem; /* Padding inside input fields */
        font-size: 1rem; /* Font size for input text */
        border: 1px solid #ccc; /* Border for the input fields */
        border-radius: 0.25rem; /* Rounded corners for the inputs */
        margin-top: 0.5rem; /* Space between label and input */
        width: 100%; /* Full width of the container */
        box-sizing: border-box; /* Include padding in the element's width */
    }

    button {
        padding: 1rem; /* Padding inside the button */
        font-size: 1.2rem; /* Font size for button text */
        color: #ffffff; /* White text color */
        background-color: #28a745; /* Green color for the button */
        border: none; /* Remove default border */
        border-radius: 0.25rem; /* Rounded corners for the button */
        cursor: pointer; /* Pointer cursor on hover */
        transition: background-color 0.3s ease; /* Smooth transition for hover effect */
    }

    button:hover {
        background-color: #218838; /* Darker green color on hover */
    }

    footer {
        margin-top: 1.5rem; /* Space above the footer */
        text-align: center; /* Center align footer text */
        font-size: 1rem; /* Font size for footer text */
    }

    footer a {
        color: #007bff; /* Link color */
        text-decoration: none; /* Remove underline */
        font-weight: bold; /* Bold text for emphasis */
    }

    footer a:hover {
        text-decoration: underline; /* Underline on hover for better visibility */
    }
</style>
