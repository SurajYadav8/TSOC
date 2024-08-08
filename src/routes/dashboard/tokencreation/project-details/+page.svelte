<script>
    let projectName = '';
    let description = '';
    let location = '';
</script>

<main>
    <h1>Enter Project Details</h1>
    <form on:submit|preventDefault={() => console.log(projectName, description, location)}>
        <label>
            Project Name
            <input type="text" bind:value={projectName} placeholder="Project Name" />
        </label>
        <label>
            Description
            <input type="text" bind:value={description} placeholder="Project Description" />
        </label>
        <label>
            Location
            <input type="text" bind:value={location} placeholder="Project Location" />
        </label>
        <button type="submit">Next</button>
    </form>
</main>
