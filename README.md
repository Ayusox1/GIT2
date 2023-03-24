# GIT2
<!DOCTYPE html>
<html>
<head>
	<title>Juego de supervivencia</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
		body {
			background-color: #111;
			color: #fff;
			font-family: Arial, sans-serif;
			font-size: 16px;
		}
		.container {
			max-width: 800px;
			margin: 0 auto;
			padding: 20px;
		}
		.header {
			text-align: center;
			margin-bottom: 20px;
		}
		.title {
			font-size: 36px;
			margin: 0;
		}
		.subtitle {
			font-size: 24px;
			margin: 0;
		}
		.content {
			display: flex;
			flex-wrap: wrap;
			justify-content: space-between;
			align-items: flex-start;
		}
		.card {
			width: calc(33.33% - 20px);
			margin-bottom: 20px;
			background-color: #222;
			border-radius: 10px;
			padding: 20px;
			box-sizing: border-box;
		}
		.card img {
			max-width: 100%;
			border-radius: 5px;
		}
		.card h2 {
			font-size: 24px;
			margin-top: 0;
		}
		.card p {
			font-size: 16px;
			margin-bottom: 0;
		}
		.card button {
			background-color: #fff;
			color: #222;
			padding: 10px 20px;
			border-radius: 5px;
			border: none;
			cursor: pointer;
		}
		.card button:hover {
			background-color: #333;
			color: #fff;
		}
	</style>
</head>
<body>
	<div class="container">
		<header class="header">
			<h1 class="title">Juego de supervivencia</h1>
			<p class="subtitle">¡Sobrevive en un mundo hostil!</p>
		</header>
		<main class="content">
			<div class="card">
				<img src="img/item1.jpg" alt="Item 1">
				<h2>Item 1</h2>
				<p>Descripción del item 1</p>
				<button>Recoger</button>
			</div>
			<div class="card">
				<img src="img/item2.jpg" alt="Item 2">
				<h2>Item 2</h2>
				<p>Descripción del item 2</p>
				<button>Recoger</button>
			</div>
			<div class="card">
				<img src="img/item3.jpg" alt="Item 3">
				<h2>Item 3</h2>
				<p>Descripción del item 3</p>
				<button>Recoger</button>
			</div>
			<div class="card">
				<img src="img/item4.jpg" alt="Item 4">
				<h2>Item 4</h2>
				<p>Descripción del item 4</p>
				<button>Recoger</button>
			</div>
</main>
</div>
</body>
</html>
