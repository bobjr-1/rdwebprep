## Template Bubble Chart

<script src="plotly-latest.min.js"></script>

<div id="myDiv"><!-- Plotly chart will be drawn inside this DIV --></div>

  <script>
var trace = [{
  x: [1, 2, 3],
  y: [1, 2, 3],
  marker: {
  	color: [’red’,’blue’],
	size: [20, 50, 80]}, mode : ’markers’};
}];

Plotly.newPlot('myDiv', [trace]);
  </script>

