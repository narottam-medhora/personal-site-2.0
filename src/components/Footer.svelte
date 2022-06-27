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

        padding: 16px;
    }

    @media screen and (max-width: 480px) {
        footer {
            font-size: .8em;
        }
    }
</style>