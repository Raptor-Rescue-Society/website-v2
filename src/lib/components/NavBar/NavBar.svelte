<nav>
	<menu>
		<li>BUTTON</li>
		<li>BUTTON</li>
		<li>BUTTON</li>
	</menu>
	<a href="/">
		<img src="/logoMain.png" alt="The Raptor Rescue Society Logo" />
	</a>
</nav>

<style>
	nav {
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		display: flex;
	}

	a {
		flex: 1;
		border: 2px solid blue;
		display: flex;
		justify-content: center;
		height: 20rem;

		background-color: var(--white-main);
	}

	img {
		aspect-ratio: 93/50;
		height: 100%;
		border: 2px solid deeppink;
	}

	menu {
		flex: 3;
		border: 2px solid red;
		height: 5rem;
	}
</style>
