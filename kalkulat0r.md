<!doctype html>
<html>
	<head>
		<meta charset=UTF-8>
		<style>
			.container {
				display: grid;
				grid-template-columns: repeat(4, 60px);
				grid-template-rows: repeat(5, 60px);
			}
			.row {
				outline: 1px solid black;
				text-align: center;
				font-size: 30px;
			}
			.button0 {
				grid-column-start: 1;
				grid-column-end: 3;
			}
			.tlo-pomarancz {
			background-color: orange;
			color: white;
			}
			.tlo-szary {
			background-color: grey;
			}
		</style>
	</head>
	
	<body>
		<div class="container">
			<div class="row tlo-szary">C</div>
			<div class="row tlo-szary">%</div>
			<div class="row tlo-szary"><-</div>
			<div class="row tlo-pomarancz">\</div>
			<div class="row tlo-szary">7</div>
			<div class="row tlo-szary">8</div>
			<div class="row tlo-szary">9</div>
			<div class="row tlo-pomarancz">x</div>
			<div class="row tlo-szary">4</div>
			<div class="row tlo-szary">5</div>
			<div class="row tlo-szary">6</div>
			<div class="row tlo-pomarancz">-</div>
			<div class="row tlo-szary">1</div>
			<div class="row tlo-szary">2</div>
			<div class="row tlo-szary">3</div>
			<div class="row tlo-pomarancz">+</div>
			<div class="row button0 tlo-szary">0</div>
			<div class="row tlo-szary">.</div>
			<div class="row tlo-pomarancz">=</div>
		</div>
	</body>
</html>
