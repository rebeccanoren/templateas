<script>
	let logo = 'resources/logo.svg';
</script>

<header>
	<nav>
		<img alt="Logo" src={logo} />
	</nav>
</header>

<style>
	header {
		display: flex;
	}

	nav {
		flex: 1;
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-content: center;
		width: 100%;
		margin: 0;
	}

	img {
		padding: 16px 0 8px;
	}

</style>
