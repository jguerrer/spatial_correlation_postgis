# spatial_correlation_postgis
A small set of postgis functions to extract some spatial correlation values like  I of Moran. Highly experimental

The basic function is given a spatial layer (2D), and a column , a spatial correlation index is computed. If a subset is selected, the values are still compoed.

The layer must  be a partition. and topologically correct, i.e.. No overlaps, well formed and so on.


