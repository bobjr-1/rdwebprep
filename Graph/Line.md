## Template Line Chart

<script src="plotly-latest.min.js"></script>

<div id="myDiv"><!-- Plotly chart will be drawn inside this DIV --></div>

  <script>
var trace1 = {
  x: [1, 2, 3, 4], 
  y: [10, 25, 13, 17], 
  type: 'scatter'
};
var trace2 = {
  x: [1, 2, 3, 4], 
  y: [16, 5, 11, 9], 
  type: 'scatter'
};
var data = [trace1, trace2];
Plotly.newPlot('myDiv', data);
  </script>

