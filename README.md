## Humanitarian data analysis - Ebola outbreaks

Notebook `index.ipynb` hosted on Binder -> [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/eleonore9/ebola_outbreaks/)
Running the notebooks saves the interactive plots on binder's server

### Data source

CSV of Ebola outbreaks before 2014 from the humanitarian data exchange (HDX).
See [here](https://data.hdx.rwlabs.org/dataset/ebola-outbreaks-before-2014)

### Using [`Altair`](http://altair-viz.github.io/):
* Notebook: `try-altair`
* html: `index.html`

### Old_notebooks

#### Tools:
Python, Jupyter notebook, Pandas, GeoPandas, GeoPy + cartodb

#### Fixing/adding info:

* Get the date range into a start date and en date. [Notebook](https://github.com/Eleonore9/ebola_outbreaks/blob/master/old_notebooks/1_format_dates_add_duration.ipynb)

* Get countries 2 letters ISO code. [Notebook](https://github.com/Eleonore9/ebola_outbreaks/blob/master/old_notebooks/2_add_iso_countries_codes.ipynb)

* Add coordinates using GeoPy. [Notebook](https://github.com/Eleonore9/ebola_outbreaks/blob/master/old_notebooks/3_add_coordinates.ipynb)

* Add geometry. [Notebook](https://github.com/Eleonore9/ebola_outbreaks/blob/master/old_notebooks/4_add_geometry.ipynb)

#### Visualisations:
* Exploring the data set with Pandas and Bokeh. [Notebook1](https://nbviewer.jupyter.org/github/Eleonore9/ebola_outbreaks/blob/master/old_notebooks/6_exploring_the_dataset.ipynb), [Notebook2](https://nbviewer.jupyter.org/github/Eleonore9/ebola_outbreaks/blob/master/index.ipynb)

![bokeh-plot](img/ebola_victims.png)


* [Cartodb map](https://eleo.cartodb.com/viz/eb27aace-9475-11e5-b6d6-0ecd1babdde5/public_map)

![map-ebola-subtypes](img/ebola_outbreaks_before_2014_1_by_eleonore_11_28_2015.png)

#### Other:
* Geocoding with GeoPy + plotting with Geoplotlib and Folium. [Notebook](https://nbviewer.jupyter.org/github/Eleonore9/ebola_outbreaks/blob/master/old_notebooks/geopy_geoplotlib_folium.ipynb)
