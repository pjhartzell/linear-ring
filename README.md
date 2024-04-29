- `minimal.ipynb` contains an example that generates an error that I am
  experiencing when loading and reprojecting MODIS data with Dask. The error occurs
  when working with MODIS data that exists in a sinusoidal projection tile whose bounds
  are on the edge of the projection and cross the antimeridian. Note that the data does
  not cross the antimeridian. The example tile is h10v02. [Link](https://modis-land.gsfc.nasa.gov/MODLAND_grid.html) to projection tile grid visual.
- The `requirements.txt` file contains the pinned dependencies for project I'm working on.