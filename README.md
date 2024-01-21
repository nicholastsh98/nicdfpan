This is the 1st version of the a web-based application deployed on render as part of Nicholas's Final Year Bachelor Thesis Requirements.
The application is based on the data captured by Rohde & Schwarz's Monitoring Receivers, primarily the PR200 and EM200 variants.

It performs analysis, through interactive visualistions for spectrum monitoring, with an adjustable threshold to filter the various signals of interest, providing frequency and bandwidth calculation information.
Angle of Arrival(AoA) data is also tabulated based on the various signals of interest, where the angles can be used to gauge the location of transmitter.

Machine Learning is also used in the form of Density-Based Spatial Clustering of Applications with Noise (DBSCAN), effecting finding trends based on the AoA data.

It is constructed as a Dash application, where an interactive dashboard that allows users to upload .bin or .rtr files based on recordings via the aforementioned receivers.

It can be assessed here: https://dfpanapp.onrender.com/
