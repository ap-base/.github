# APBase

**Intelligence in geospatial processing for precision agriculture.**

APBase turns raw field data, such as yield monitors, soil samples and sensor grids, into reliable precision maps with a single call. It removes invalid points and spatial outliers on its own, builds the grid, and picks the interpolation model with the lowest cross-validation error. No manual tuning is needed.

The core runs on native Fortran kernels with OpenMP, wrapped in a lightweight Python package with no web framework or database. The same input always gives the same map, and the same pipeline runs in a notebook, GIS plugins, APIs, workers, containers and AI agents through MCP servers.

Get started with `pip install apbase` and see the docs at [apbase.io](https://apbase.io).
