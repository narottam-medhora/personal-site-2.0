<main>
    <div>
        <h1>Narottam Medhora | Data Journalist</h1>
        <p>Under <span>(re)</span>construction using <a href="https://kit.svelte.dev/" alt="SvelteKit">SvelteKit</a> and <a href="https://vercel.com/" alt="Vercel">Vercel</a>.</p>
    </div>
</main>

<style>
	:root {
		/* Sizes */
		--main-h1-size: 2em;

		/* Colors */
		--main-link-color: rgb(2, 151, 249);
		--main-link-visited: rgb(255, 166, 0);
	}

	main {
		margin-block-start: 1em;
		text-align: center;
	}

	/* TYPOGRAPHY */
	h1 {
		font-size: var(--main-h1-size);
	}

	p {
		margin-block-start: 1em;
		line-height: 1.4;
	}

	span {
		color: tomato;
	}

	/* LINKS */
	a {
		outline: none;
		text-decoration: none;
		padding: 2px 1px 0;
	}

	a:link {
		color: var(--main-link-color);
	}

	a:visited {
		color: var(--main-link-visited)
	}

	a:focus, a:hover {
		border-bottom: 1px solid;
	}

	a:active {
		color: red;
	}

	a[href^="http"] {
		background: url('static/logos/icons8-external-link-26.png') no-repeat 100% 0;
		background-size: 16px 16px;
		padding-right: 19px;
	}
</style>