# plotlyhtmlexporter

Plotly friendly, Jupyter Notebook HTML Exporter.

## Installation:

  - Using `pip`:

```
$ pip install plotlyhtmlexporter
```

  - From Source:

```
  $ git clone https://github.com/tarzzz/plotlyhtmlexporter
  $ cd plotlyhtmlexporter
  $ python setup.py
```

## Usage:

  - From Command Line (with NBConvert):

```
$ jupyter nbconvert --to plotlyhtml mynotebook.ipynb
```

  - From the Python interpreter:

```
>>> from plotlyhtmlexporter import PlotlyHTMLExporter
>>> exp = PlotlyHTMLExporter()
>>> body, resources = exp.from_notebook_node(nb)
```
