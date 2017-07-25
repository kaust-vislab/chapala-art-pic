## Cyclone Chapala over the Arabian Sea
![Cyclone Chapala](pics/cyclone_small.png)

## Background

The [cyclone Chapala](https://en.wikipedia.org/wiki/Cyclone_Chapala), which formed over the Arabian Sea end of October 2015, took advantage of the warmest waters ever recorded in the Arabian Sea and rapidly intensified to a Category 4 storm with 155 mph winds and with a central pressure of 944 hPa. This made Chapala the second strongest tropical cyclone on record in the Arabian Sea, behind Cyclone Gonu in 2007.

It affected as many as 1.1 million people, displacing more than 36,000. The track of this cyclone is also very interesting as it moved into the Gulf of Aden, pushing waters into the Red Sea through the narrow straits of Bab-el-Mandeb. This might have significant impact on the marine-eco system over the Gulf of Aden and the Red Sea.

## Simulation

For the numerical simulation on Shaheen II we used [WRF](http://www.wrf-model.org) version 3.7.1. The implemented configuration is composed of two, two-way interactive nested domains with horizontal resolutions of 9 km and 3 km respectively. The vertical column is discretized into 34 vertical levels.

The simulation results are generated on a 1100 × 1000 × 34 regular grid with 138 time steps. Data size for each time step is about 3.1 GB. Therefore, the total size of the generated data set is roughly 428 GB. The simulation was performed in 3 hours using 640 cores on our newly established High Performance Computational Facility [Shaheen II](https://www.hpc.kaust.edu.sa/content/shaheen-ii)

## Visualization

## References

T. Theußl, H. P. Dasari, I. Hoteit and M. Srinivasan, "[Simulation and visualization of the cyclonic storm chapala over the arabian sea: a case study](http://ieeexplore.ieee.org/abstract/document/7756074/)," 2016 4th Saudi International Conference on Information Technology (Big Data Analysis) (KACSTIT), Riyadh, 2016, pp. 1-6.
