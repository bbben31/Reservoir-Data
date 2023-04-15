# Reservoir-Data

The reservoir data system supports storage of salinity and Calcium concentration (PPM)
values from various devices, located at strategic locations within a fresh water reservoir. It
also has a device registry.

The data is stored in MongoDB. The focus of the project is to learn some data modeling in
MongoDB and to implement various functionalities based on that.

Each device sends either salinity or Calcium PPM data based on its type. There is only one
category of user - admin.
