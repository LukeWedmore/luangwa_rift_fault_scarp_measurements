# Luangwa Rift Fault Scarp Measurements

Scarp height measurements for faults in the Luangwa Rift performed by Tess Turner for her University of Bristol MSci Earth Sciences final year project.

If you use these measurements please cite the following paper in addition to this dataset:

Turner, T., Wedmore, L.N.J., Biggs, J., Williams, J. Sichingabula, H.M., Kabumbu, C. Banda, K. The Luangwa Rift Active Fault Database and fault reactivation along the southwestern branch of the East African Rift. _In preparation for Solid Earth_

These measurements were performed on SRTM data using the method outlined in [Wedmore et al., 2020]. Topographic profiles were sampled event 30 m and stacked at 120 m intervals along strike.

Four faults in the Luangwa Rift have been measured using this technique: The Chipola, Chitembo, Kabungo and Molaza faults. The traces of these faults, and all other known active faults in the Luangwa Rift have been separately archived as part of the [Luangwa Rift Active Fault Database].

## Data Format

Files are provided in comma separated value ([csv]) format. Each file contains one header line with descriptions of the data contained within each column. The column headings and extra information are summarised in the table below. Where data columns #5-10 are blank, this is because no measurements were possible in the profile corresponding to that particular row number. If columns 11-16 are blank, this is because there are no scarp height measurements within the sampling window of the moving average.

### Attribute Table
Column # | Attribute                            | Units            | Data Type     | Notes
---------|--------------------------------------|------------------|---------------|--------------------------------------------------
1        | Longitude                            | decimal degrees  | Float         |  
2        | Latitude                             | decimal degrees  | Float         | 
3        | Distance Along Fault                 | kilometers       | Float         |
4        | Distance Along Fault                 | meters           | Integer       |
5        | Scarp Height                         | meters           | Float         | Mean scarp height measurement of 10,000 iterations of scarp height with varying subset of points in the hanging wall, scarp and footwall slopes.
6        | Scarp Height Standard Deviation      | meters           | Float         | Standard deviation of 10,000 iterations of meausuring the scarp height with varying subset of points in the hanging wall, scarp and footwall slopes
7        | Upper Slope Angle                    | degrees          | Float         | Mean upper slope dip angle of 10,000 iterations of subset of points selected from the footwall slope (above the top of the fault scarp).
8        | upper Slope Angle Standard Deviation | degrees          | Float         | Standard devation of upper slope angle of 10,000 random subsets of the points selected on the upper slope of the fault.
9        | Lower Slope Angle                    | degrees          | Float         | Mean lower slope dip angle of 10,000 iterations of subset of points selected from the hanging wall slope.
10       | lower Slope Angle Standard Deviation | degrees          | Float         | Standard devation of lower slope angle of 10,000 random subsets of the points selected on the lower slope of the fault.
11       | Filtered median offset (1 km)        | meters           | Float         | median scarp height over 1 km  of the distance along strike (0.5 km either side of the point).
12       | filtered standard deviation (1km)    | meters           | Float         | standard deviation scarp height over 1 km  of the distance along strike (0.5 km either side of the point).
13       | Filtered median offset (3 km)        | meters           | Float         | median scarp height over 3 km  of the distance along strike (1.5 km either side of the point).
14       | filtered standard deviation (3km)    | meters           | Float         | standard deviation scarp height over 3 km  of the distance along strike (1.5 km either side of the point).
15       | Filtered median offset (5 km)        | meters           | Float         | median scarp height over 5 km  of the distance along strike (2.5 km either side of the point).
16       | filtered standard deviation (5km)    | meters           | Float         | standard deviation scarp height over 5 km  of the distance along strike (2.5 km either side of the point).

## Version Control
A static version of this dataset will be archived on the [Zenodo] data archive as part of the publication Turner et al. It is intended that this database will be updated in the future as high resolution topography products become available and/or methods for measuring fault scarps improve. Please contact Luke Wedmore <luke.wedmore@bristol.ac.uk> for more information or if you spot any errors.

### References
Wedmore, L.N.J., Biggs, J., Williams, J.N., Fagereng, Å., Dulanya, Z., Mphepo, F., Mdala, H. (2020) Active Fault Scarps in Southern Malawi and Their Implications for the Distribution of Strain in Incipient Continental Rifts. _Tectonics_, 39(3), e2019TC005834, [doi.org/10.1029/2019TC005834]

[csv]: https://datatracker.ietf.org/doc/html/rfc4180
[Wedmore et al., 2020]: https://doi.org/10.1029/2019TC005834
[Luangwa Rift Active Fault Database]: https://github.com/LukeWedmore/luangwa_rift_active_fault_database
[Zenodo]: https://zenodo.org/
[doi.org/10.1029/2019TC005834]: https://doi.org/10.1029/2019TC005834
