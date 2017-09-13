## Template Map

<script src="plotly-latest.min.js"></script>

<div id="Div1"><!-- Plotly chart will be drawn inside this DIV --></div>

&nbsp;test

<div id="Div2"><!-- Plotly chart will be drawn inside this DIV --></div>

  <script>
var data = [{
        type: 'scattergeo',
        mode: 'markers',
        locations: ['FRA', 'DEU', 'RUS', 'ESP'],
        marker: {
            size: [20, 30, 15, 10],
            color: [10, 20, 40, 50],
            cmin: 0,
            cmax: 50,
            colorscale: 'Greens',
            colorbar: {
                title: 'Some rate',
                ticksuffix: '%',
                showticksuffix: 'last'
            },
            line: {
                color: 'black'
            }
        },
        name: 'europe data'
    }];

    var layout = {
        'geo': {
            'scope': 'europe',
            'resolution': 50
        }
    };

    Plotly.plot('Div1', data, layout);
</script>

  <script>
var databar = [{
  x: ['oranges', 'pommes', 'poires'],
  y: [20, 14, 29],
  type: 'bar'
}];

    Plotly.plot('Div2', databar);
</script>


