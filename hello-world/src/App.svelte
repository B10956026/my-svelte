<script>
	const name = '謝東翰'
	const channel = '<b>國立屏東科技大學 資訊管理系</b>'
	const hack = `<a href="#" onclick="alert('You have been hacked!')">Win a prize!'<a/>`
	const id = 'heading'
	const disabled = false
</script>

<main>
	<h1>B10956026 {name}</h1>
	<div>{@html channel}</div>
	<div>{@html hack}</div>
	<h2 {id}>This is a heading</h2>
	<button {disabled}>Bind</button>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>