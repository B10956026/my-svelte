<script>
	const name = '謝東翰'
	const channel = '<b>國立屏東科技大學 資訊管理系</b>'
	const hack = `<a href="#" onclick="alert('您已被黑客攻擊！')">恭喜中獎!'<a/>`
	const id = 'heading'
	const disabled = true
	const status = 'success'
	const promoted = true
</script>

<main>
	<h2 class="underline">桜巫女（さくらみこ）</h2>
	<h2 class={status}>狀態</h2>
	<h2 class:promoted>Hololive Production</h2>
	
	<h1>B10956026 {name}</h1>
	<div>{@html channel}</div>
	<div>{@html hack}</div>
	<h2 {id}>This is a heading</h2>
	<button {disabled}>Bind</button>
</main>

<style>
	.underline {
		text-decoration: underline;
	}

	.danger {
		color:red;
	}

	.success {
		color:green;
	}

	.promoted {
		font-style: italic;
	}

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