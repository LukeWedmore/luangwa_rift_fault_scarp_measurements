# Luangwa Rift Fault Scarp Measurements

Scarp height measurements for faults in the Luangwa Rift performed by Tess Turner for her University of Bristol MSci Earth Sciences final year project.

These measurements were performed on SRTM data using the method outlined in [Wedmore et al., 2020].

If you use these measurements please cite the following paper in addition to this dataset:

Turner, T., Wedmore, L.N.J., Biggs, J., Williams, J. Sichingabula, H.M., Kabumbu, C. Banda, K. The Luangwa Rift Active Fault Database and fault reactivation along the southwestern branch of the East African Rift. _In preparation for Solid Earth_

## Data Format

Files are provided in comma separated value ([csv]) format. Each file contains one header line with descriptions of the data contained within each column. The column headings and extra information are summarised in the table below.

### Attribute Table
Column # | Attribute                        | Units            | Data Type     | Notes
---------|----------------------------------|------------------|---------------|--------------------------------------------------
1        | Longitude                        | decimal degrees  | Float         |  
2        | Latitude                         | decimal degrees  | Float         | 
3        | Distance Along Fault             | kilometers       | Float         |
4        | Distance Along Fault             | meters           | Integer       |
5        | Scarp Height                     | meters           | Float         | 
6        | Scarp Height Standard Deviation  | meters           | Float         | Standard deviation of 10,000 iterations of meausuring the scarp height with varying subset of points in the hangingwall, scarp and footwall slopes
7        | Upper Slope Angle                | Degrees          | Float         |
8
9
10
11
12
13
14
15
16
17


### References
Wedmore, L.N.J., Biggs, J., Williams, J.N., Fagereng, Å., Dulanya, Z., Mphepo, F., Mdala, H. (2020) Active Fault Scarps in Southern Malawi and Their Implications for the Distribution of Strain in Incipient Continental Rifts. _Tectonics_, 39(3), e2019TC005834, doi.org/10.1029/2019TC005834

[csv]: https://datatracker.ietf.org/doc/html/rfc4180
[Wedmore et al., 2020]: https://doi.org/10.1029/2019TC005834
