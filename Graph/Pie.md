## Template Pie Chart

<script src="plotly-latest.min.js"></script>
<script src="numeric.min.js"></script>

<div id="myDiv"><!-- Plotly chart will be drawn inside this DIV --></div>

  <script>
var data = [{
  values: [19, 26, 55],
  labels: ['Residential', 'Non-Residential', 'Utility'],
  type: 'pie'
}];

Plotly.newPlot('myDiv', data);
  </script>

