The subfolders in this folder contain the topographic profiles that were extracted from SRTM data. These profiles were measured to generate the scarp height database contained in this repository.

The profile number corresponds to the row number (minus the header line) in the corresponding fault measurement files. The location and distance along strike of the fault is also provided in the individual fault metadata file within this directory.

The format of the profiles are as follows:

Column | Data
-------|----------
1      | Distance across strike (m)
2      | Median elevation of stacked profiles (m)
3      | Minimum elevation of profiles that were stacked (m)
4      | Maximum elevation of profiles that were stacked (m)
5      | lower confidence bound (m)
6      | upper confidence bound (m)
