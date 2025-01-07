# lakes_cci_tools

Lakes have been observed as sentinels of climate change, both directly and indirectly through watershed changes. Lakes integrate responses over time and studies of globally distributed lakes can capture different aspects of climate change. Therefore, a global and consistent climate data record of lakes is essential to mitigate and adapt to climate change. 

The overarching objective of the Lakes project (https://climate.esa.int/en/projects/lakes/) funded by ESA,  is to produce and validate a consistent data set of the variables grouped under the Lakes ECV.

Contact: cci-lakes.contact@groupcls.com

The objective of this repository is to group a set of scripts than may be useful for the lakes_cci data user community 

Available scripts:

* <b>lakes_cci_download.ipynb</b>: a jupyter notebook to download files on a defined zone and period of time. Daily output files include all the ECV variables. This script is useful for downlading data for several lakes in a region where latitude and longitude boundaries are known. 

* <b>lakes_cci_download1lake_by_id.ipynb</b>: a jupyter notebook to downlad files for a given lake. Daily output files include all the ECV variables. This script is useful for dowloading data for a single lake. Information about its boundaries is not required.

* <b>lakes_cci_download1variable1lake_by_id.ipynb</b>: a jupyter notebook to download a single variable for a given lake based in the lakes_cci id. 

* <b>lakes_cci_data_availability.ipynb</b>: a jupyter notebook to visualize data product available for a given lake during a period of time. This script is useful for identifying the files to be download.

* <b>lakes_cci_mean_timeseries.ipynb</b>: a jupyter notebook to generate a timeseries of the mean value of a variable for a lake_id for lakes_cci version 2.1.0

* <b>lakes_cci_binder.ipynb</b>: this jupyter notebook allows to generate a set of figures relating to a variable for a lake in lakes_cci version 2.1.0 based in its id. It is adapted to be executed via Binder (https://mybinder.org/)

