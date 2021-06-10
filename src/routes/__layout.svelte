<header>Welcome!</header>
<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
</nav>

<!-- When a page loads from the routes directory it first loads everything in __layout.svelte and then puts the pages html in this slot -->
<main>
	<slot />
</main>

<footer>Copyright 2021</footer>
