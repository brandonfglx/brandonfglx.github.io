<div align="center">
	<h1>Brandon's Site</h1>
	<picture>
		<img alt="Brandon Li's Personal Website" src="https://raw.githubusercontent.com/bhlcusd/bhlcusd.github.io/refs/heads/main/resources/page-short.png" width="80%" />
	</picture>
	<h3>A website with a personal touch.</h3>
</div>

## Quick Start Guide
Explore the website: **[Try It Now!](https://bhlcusd.github.io)**

## Features
 - **Simple, Yet Modern Design** - Rounded borders and dark mode support
 - **About Me** - Concise information about the developer
 - **Contacts** - Easy-to-see icons to the developer's social media pages
 - **Flexible** - Designed to be scalable onto any form factor

## Technicals
 - **Built on Svelte** - Chosen for its balance between bog-standard HTML & CSS and its compatibility with more complex build systems (like Bun). Even though TypeScript is not used in this project, using Svelte gives more flexibility for the developer to extend the website later in the future.
 - **TailwindCSS** - Instead of writing CSS classes by hand, TailwindCSS was used to pre-define the generic CSS classes needed for this relatively simple project
 - **Mobile-First Design** - Throughout the project, mobile-first design was implemented (i.e. make the website scale outwards to larger screens); experimented with Flexbox and Grid layouts to scale properly without too much wasted space
 - **Customized GitHub Actions Runner** - Due to the dynamic nature of Svelte, the default `github-pages` runner does not interface well with Svelte. Instead, the project bundles a new [`deploy.yml`](.github/workflows//deploy.yml) file that automatically installs all dependencies, builds the project, and loads the static files for GitHub Pages.

## Acknowledgements
 - **Svelte & SvelteKit Documentation** - Assisted in the setup process and converting it into a static webpage using `adapter-static`.
 - **TailwindCSS Documentation** - Assisted in finding corresponding CSS tags
