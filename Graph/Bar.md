## Template Bar Chart

<script src="plotly-latest.min.js"></script>

<div id="myDiv"><!-- Plotly chart will be drawn inside this DIV --></div>

  <script>
var data = [{
  x: ['oranges', 'pommes', 'poires'],
  y: [20, 14, 29],
  type: 'bar'
}];
Plotly.newPlot('myDiv', data);
  </script>

