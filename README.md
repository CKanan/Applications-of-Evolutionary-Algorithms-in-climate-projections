# Applications of Evolutionary Algorithms in climate projections
Finding sine equations for climate phenomena.

## Abstract

The global climate is a chaotic and complex system. The climate system constantly changes
due to internal variability and natural external perturbation. The earth’s axial rotation causes daily
changes in temperature, precipitation, cloud cover, humidity and other climate variables. Over
short time scales (ranging from minutes to several days) movement of clouds, air masses, and
fronts contribute to rapid, often unpredictable, changes in weather. The earth’s annual rotation
about the sun causes large seasonal changes in climate. Multi-annual to decade mode transitions
such as the El Nino and La Nina cycles in the Pacific cause additional variability in the climate
system. Therefore, determining the global effects of ENSO occurrences is considered one of the
important issues.

In this thesis, applications of Machine Learning and Evolutionary Algorithms on the global cli-
mate are presented. El Nino and La Nina events are classified according to Oceanic Nino Index val-
ues using Machine Learning classification methods and are also classified according to their shapes
by eye and automatically by ML clustering methods. The equations are found for events using EAs
where Genetic Programming is used to find average equations for groups and Real Valued Genetic
Algorithm is used to find equation of each event with changing parameters of average equation.
These algorithms are worked on island model in GPU programming to reduce time computation.
Using equations, geophysicists and meteorologists can better understand climatic phenomena and
make new analysis on these phenomena.

![walker_circ](https://github.com/CKanan/Applications-of-Evolutionary-Algorithms-in-climate-projections/assets/49164758/e534c9bf-6e3c-412d-a0c2-26783b5b32ab)

Schematic diagrams of (a) normal, (b) El Nino and (c) La Nina conditions. On the left side of each diagram is the western Pacific Ocean, near Asia, and on the right is the eastern Pacific Ocean, near South America. Warm ocean surface temperatures are indicated by red/orange colors, whereas cooler water is indicated by yellow/greenish colors. In the tropics, the thermocline is the depth at which the water temperature is around 20°C. Deep convective clouds rise over the pool of warm water. The warm pool of water flows eastward during El Nino (b), and the thermocline's slope flattens. The warm pool flows westward during La Nina (c), and the thermocline's slope steepens. (Source: NASA; see https://www.pmel.noaa.gov/elnino/schematic-diagrams )

## Data

I used Oceanic Nino Index (ONI) dataset from Climate Prediction Center of the National
Oceanic and Atmospheric Administration (NOAA) (Data source : https://origin.cpc.ncep.noaa.gov/products/analysis_monitoring/ensostuff/ONI_v5.php). It is the running 3-month mean Sea Sur-
face Temperature (SST) anomaly for the Nino 3.4 region which located in the intervals [5° South;
5° North] and [170° West; 120° West] in the Pacific ocean.

![nino34](https://github.com/CKanan/Applications-of-Evolutionary-Algorithms-in-climate-projections/assets/49164758/92613dd1-5019-489e-8569-976bd19d7ce7)

This dataset covers ONI time series from 1950 to present. During the period covered by this
dataset, 26 El nino and 24 La nina events occurred. The index is defined as the aver-
age of monthly SST anomalies. The monthly anomalies are calculated by subtracting the average
temperature in the same month over the past 30 years. Then the running three-months average is
calculated.

![data](https://github.com/CKanan/Applications-of-Evolutionary-Algorithms-in-climate-projections/assets/49164758/06ccf1ed-4abb-424a-ab1c-a7faf620dffc)







