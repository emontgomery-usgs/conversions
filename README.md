# conversions
#
# this for code to check metadata and changing between EPIC and CF conventions in netCDF files
#
# historically our netCDF files follow the EPIC convention, and we have a program to convert them to CF-1.6
# https://github.com/USGS-CMG/usgs-cmg-portal/tree/master/woods_hole_obs_data
#
# but as more people are writing in python, use of CF style is built in, so we're needing more utilities to treat different circumstances
#
# PLUS- the CF-1.6 data we harvest to the portal has specific elements that may or may not be included in a "generic" CF file,
# so something to deal with adding any needed elements is needed
