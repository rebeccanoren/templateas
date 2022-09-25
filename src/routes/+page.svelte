<script>
  let illustration = 'resources/illustration.svg';
</script>

<svelte:head>
	<title>Templateas</title>
	<meta name="description" content="Templateas" />
</svelte:head>

<section class="work">
	<img alt="Illustration of a person building" src={ illustration}/>
	<h1>We are building this site
	</h1>
	<h2>Promise to come back soon for more 💖</h2>	
	<a href="https://www.etsy.com/shop/Templateas"><button>I'll check out the Etsy shop</button></a>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

</style>
