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

\begin{figure}[H]
    \centering
    \includegraphics[scale=0.4]{img/walker_circ.png}
    \caption{Schematic diagrams of (a) normal, (b) El Nino and (c) La Nina conditions. On the left side of each diagram is the western Pacific Ocean, near Asia, and on the right is the eastern Pacific Ocean, near South America. Warm ocean surface temperatures are indicated by red/orange colors, whereas cooler water is indicated by yellow/greenish colors. In the tropics, the thermocline is the depth at which the water temperature is around 20°C. Deep convective clouds rise over the pool of warm water. The warm pool of water flows eastward during El Nino (b), and the thermocline's slope flattens. The warm pool flows westward during La Nina (c), and the thermocline's slope steepens. (Source: NASA; see \href{https://www.pmel.noaa.gov/elnino/schematic-diagrams}{www.pmel.noaa.gov/elnino/schematic-diagrams})}
    \label{fig:walker}
\end{figure}
