## Template Bar Chart

<script src="plotly-latest.min.js"></script>

<div id="myDiv"><!-- Plotly chart will be drawn inside this DIV --></div>

  <script>
var trace1 = {
  x: ['oranges', 'pommes', 'poires'],
  y: [20, 14, 23],
  name: 'SF Zoo',
  type: 'bar'
};

var trace2 = {
  x: ['oranges', 'pommes', 'poires'],
  y: [12, 18, 29],
  name: 'LA Zoo',
  type: 'bar'
};

var data = [trace1, trace2];

var layout = {barmode: 'stack'};

Plotly.newPlot('myDiv', data, layout);  </script>

---------

<table>
<tr>
<td><div id="DivLeft"></div></td>
<td><div id="DivRight"></div></td>
</tr>
</table>

  <script>
var trace1 = {
  x: ['oranges', 'pommes', 'poires'],
  y: [20, 14, 23],
  name: 'SF Zoo',
  type: 'bar'
};

var trace2 = {
  x: ['oranges', 'pommes', 'poires'],
  y: [12, 18, 29],
  name: 'LA Zoo',
  type: 'bar'
};

var data = [trace1, trace2];

var layout = {barmode: 'stack'};

Plotly.newPlot('DivLeft', data, layout);  </script>

  <script>
var trace1 = {
  x: ['oranges', 'pommes', 'poires'],
  y: [20, 14, 23],
  name: 'SF Zoo',
  type: 'bar'
};

var trace2 = {
  x: ['oranges', 'pommes', 'poires'],
  y: [12, 18, 29],
  name: 'LA Zoo',
  type: 'bar'
};

var data = [trace1, trace2];

var layout = {barmode: 'stack'};

Plotly.newPlot('DivRight', data, layout);  </script>
