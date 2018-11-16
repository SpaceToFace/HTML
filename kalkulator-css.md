<!doctype html>
<html>
	<head>
		<meta charset=UTF-8>
		<link href="https://fonts.googleapis.com/css?family=KoHo" rel="stylesheet">
		<style>
			.container {
				display: grid;
				grid-template-columns: repeat(4, 62px);
				grid-template-rows: repeat(7, 60px);
			}
			.row {
				outline: 1px solid black;
				text-align: center;
				font-size: 30px;
				line-height: 60px;
			}
			.button0 {
				grid-column-start: 1;
				grid-column-end: 3;
				font-family: KoHo;
				text-align:left;
			}
			.tlo-pomarancz {
			background-color: orange;
			color: white;
			 font-family: KoHo;
			}
			.tlo-szary {
			background-color: #d9d9d9;
			font-family: KoHo;
			}
			.wynik {
				grid-column-start: 1;
				grid-column-end: 5;
				grid-row-start: 1;
				grid-row-end: 3;
				background-color: black;
				color: white;
				text-align: right;
				font-family: KoHo;
			}
			span {
				content: "\2190";
				content: "\00F7";
			} 
			.zero {
				position:relative;
				left: 25px;
			}
			.wynik-format {
				position: relative;
				right: 10px;
				top: 55px;
			}
			.mobilne-dodawanie {
				grid-column-start: 4;
				grid-column-end: ;
				grid-row-start: 3;
				grid-row-end: 4;
			}
		</style>
	</head>
	
	<body>
		<div class="container">
			<div class="row wynik">
				<div class="wynik-format">2137.2137</div>
			</div>
			<div class="row tlo-szary">C</div>
			<div class="row tlo-szary">%</div>
			<div class="row tlo-szary"><span>&#8592;</span></div>
			<div class="row tlo-pomarancz mobilne-dodawanie"><span>&#247;</span></div>
			<div class="row tlo-szary">7</div>
			<div class="row tlo-szary">8</div>
			<div class="row tlo-szary">9</div>
			<div class="row tlo-pomarancz">X</div>
			<div class="row tlo-szary">4</div>
			<div class="row tlo-szary">5</div>
			<div class="row tlo-szary">6</div>
			<div class="row tlo-pomarancz">-</div>
			<div class="row tlo-szary">1</div>
			<div class="row tlo-szary">2</div>
			<div class="row tlo-szary">3</div>
			<div class="row tlo-pomarancz">+</div>
			<div class="row button0 tlo-szary">
				<div class="zero">0</div>
			</div>
			<div class="row tlo-szary">.</div>
			<div class="row tlo-pomarancz">=</div>
		</div>
	</body>
</html>

