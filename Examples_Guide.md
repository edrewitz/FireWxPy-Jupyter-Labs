# FireWxPy Jupyter Lab Tutorials Landing Page

Here are several tutorials on how users will be able to use FireWxPy to make customized weather graphics with a focus on fire weather while having MINIMAL coding proficiency. My motto is: "I want my software to do all the work so you don't have to!"

In FireWxPy users can make graphics in the following categories: Forecast Model Data, Forecast Soundings, Forecast Time Cross-Sections, Forecast Cross-Sections Between Two Points, RTMA, NWS Forecasts, SPC Outlooks, Various Types Of Observational Graphics, SAWTI (Specific to Southern California) and Daily Solar Information. 

These functions download the data, unpack, parse and plot the data automatically. These functions also build the directory that hosts the images and downloads, unzips and files the .SHP files and their components to where they need to go. That is the beauty of FireWxPy, it requires MINIMAL work on the part of the user (remember my motto!). 

If users wish to download and create a lot of graphics at once, the recommended way is to download the data outside of the 
plotting function and pass it into the plotting function. The plotting function will do all the rest of the work such as
parsing the data, plotting the data and building the branches of the directory if the user adds a new FireWxPy function to the
script they are running. 

Here are links to jupyter lab tutorials for all the aforementioned scenarios:

1) In this example, we are a first time FireWxPy user (automatic first time user set-up) and we make a plot of the latest RTMA RH data across California. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/first_time_user.ipynb)
2) In this example, we will make a medley of RTMA graphics across the NWS Alaska Region. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/multi_rtma.ipynb)
3) In this example, we will make two RTMA plots using custom decimal degree lat/lon bounds. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/rtma_custom.ipynb)
4) In this example, we will make a set of the National Weather Service Maximum Relative Humidity Forecast across Texas. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/nws_maxrh.ipynb)
5) In this example, we will make a set of the National Weather Service Maximum Relative Humidity Trend Forecast and National Weather Service Minimum Relative Humidity Trend Forecast graphics using custom decimal degree lat/lon boundaries. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/nws_custom.ipynb)
6) In this example, we will make a plot of the METAR Observations across CONUS. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/metars.ipynb)
7) In this example, we will make a set of plots showing relative humidity, temperature and wind speed as scatter plots for CONUS and New York State. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/scatter_obs.ipynb)
8) In this example, we will grid the relative, temperature and wind speed METAR observations for the South Ops Geographic Area. We also change our reference system to see the data from the GACC reference. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/gridded_obs.ipynb)
9) In this example, we will make a set of NAM Forecast 500mb Height/Vorticity/Wind graphics for CONUS. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/500mb_vorticity.ipynb)
10) In this example, we will make a GFS and NAM time cross-section forecast for Aberdeen, SD. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/KABR_cross_section.ipynb)
11) In this example, we will make NAM and RAP time cross-sections using a custom point over Lake-Ontario to analyze the snow potential at SUNY Oswego (my alma mater). - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/LO1_cross_section.ipynb)
12) In this example, we will make a RAP cross-section between one point of lat/lon on the west coast and another point of lat/lon on the east coast. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/cross_section_two_points.ipynb)
13) In this example, we will make plots of the SPC Convective Outlook and SPC Critical Fire Weather Risk Outlook for CONUS. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/spc.ipynb)
14) In this example, we will plot the daily solar information for Riverside, CA. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/solar_info.ipynb)
15) In this example, we will make a daily weather summary for Ontario International Airport (KONT). - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/KONT_Daily_Weather_Summary_Example.ipynb)
16) In this example, we will plot the Santa-Ana Wildfire Threat Index from Rolinski et al. 2016. [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/sawti.ipynb)
17) In this example, we will plot the latest observed sounding from NKX. [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/NKX_Sounding_Example.ipynb)
18) In this example, we will plot an observed sounding for a custom date/time to analyze Santa Ana Winds at NKX. [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/Santa_Ana_Wind_Sounding.ipynb)
19) In this example, we will analyze the Red Flag Warning conditions in the Southeastern CONUS using the RTMA Critical Fire Weather graphics. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/rtma_rfw.ipynb)
20) In this example, we will create a Critical Fire Weather Forecast using the National Weather Service NDFD Grids for areas where Red Flag Warnings are in effect in Wyoming. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/nws_critical_firewx12.ipynb)
21) In this example, we will plot the 18z GEFS 0.25x0.25 Ensemble Mean Favorable Fire Weather Forecast across Nebraska where the National Weather Service has issued Red Flag Warnings for 25-35 MPH winds and relative humidity as low as 20%. In this case, we will use the thresholds of sustained wind speed >= 25 MPH AND relative humidity <= 30%. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/gefs.ipynb)
22) In this example we make a large medley of graphics analyzing Red Flag Warnings extending from the central Plains through the Southwestern U.S. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/rfw_analysis.ipynb)
23) In this example we will make 8-Day Mean, EOF1, EOF2, EOF1 Scores and EOF 2 Scores GEFS 0.5x0.5 degree forecast graphics for the northern and southern hemispheres. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/mean_eofs.ipynb)
24) In this example, we will plot the GFS 700mb Geopotential Height/Relative Humidity/Wind Forecast for Central & Eastern Europe. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/International_GFS_Example.ipynb)
25) In this example, we will make graphs of the Energy Release Component (ERC) values for the South Ops Predictive Services Areas using data from FEMS. - [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/ERC_Charts.ipynb)
26) In this example, we will make GFS 0.25x0.25 degree 10-meter wind forecast graphics for the country of Guyana. [click here](https://github.com/edrewitz/FireWxPy-Jupyter-Labs/blob/main/Tutorials/Guyana.ipynb)
