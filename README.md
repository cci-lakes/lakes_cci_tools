# lakes_cci_tools

Lakes have been observed as sentinels of climate change, both directly and indirectly through watershed changes. Lakes integrate responses over time and studies of globally distributed lakes can capture different aspects of climate change. Therefore, a global and consistent climate data record of lakes is essential to mitigate and adapt to climate change. 

The overarching objective of the Lakes project (https://climate.esa.int/en/projects/lakes/) funded by ESA,  is to produce and validate a consistent data set of the variables grouped under the Lakes ECV.

Contact: cci-lakes.contact@groupcls.com

The objective of this repository is to group a set of scripts than may be useful for the lakes_cci data user community 

Available scripts:

* <b>lakes_cci_download.ipynb</b>: a jupyter notebook to download files on a defined zone and period of time. Daily output files include all the ECV variables. This script is useful for downlading data for several lakes in a region where latitude and longitude boundaries are known. 

* <b>lakes_cci_download1lake_by_id.ipynb</b>: a jupyter notebook to downlad files for a given lake. Daily output files include all the ECV variables. This script is useful for dowloading data for a single lake. Information about its boundaries is not required.

* <b>lakes_cci_data_availability.ipynb</b>: a jupyter notebook to visualize data product available for a given lake during a period of time. This script is useful for identifying the files to be download.
