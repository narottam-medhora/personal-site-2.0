<script>
    let year = new Date().getFullYear();
</script>

<footer>
    <div class="social-container">
        <a href="https://github.com/narottam90" alt="GitHub profile">GitHub</a>
        <a href="https://twitter.com/narottammedhora" alt="Twitter profile">Twitter</a>
        <a href="https://www.linkedin.com/in/narottam-medhora" alt="LinkedIn profile">LinkedIn</a>
    </div>
    <p>Narottam Medhora © {year}</p>
</footer>

<style>
    footer {
        display: grid;
        grid-template-columns: 1fr auto;
        align-items: baseline;
        margin-block-end: 1em;
        margin-inline: 1em;
        text-align: right;
        grid-row-start: 2;
        grid-row-end: 3;
    }

    .social-container {
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        align-items: baseline;
        align-items: flex-start;
    }

    .social-container a {
        padding: 1em;
    }
</style>