# MECMUS

Multi-scale Electrical Conductivity Model of continental US (MECMUS). The Jupyter notebook can be used to read in and plot models.

There are now two versions of the MECMUS model:
- The MECMUS-2025 is the newest version of the model, derived from nearly 1600 MT stations of the complete USArray, whereby both impedance tensor and inductin vectors (tippers) were inverted in 3-D. 
- The MECMUS-2022 was derived by inverting the full MT impedance tensor from 1291 USArray stations. The inversion procedure is described in the reference below. This is the previous version of the model.

In both cases, MT data was retrieved from the IRIS data portal: https://ds.iris.edu/spud/emtf

<img src="MECMUS-2025_depth_5.45km.png" width="80%" height="100%">
<img src="MECMUS-2025_depth_14.05km.png" width="80%" height="100%">
<img src="MECMUS-2025_depth_42.5km.png" width="80%" height="100%">
<img src="MECMUS-2025_depth_158.75km.png" width="80%" height="100%">

# References
- Munch, F. and Grayver, A., (2025). Multi-scale electrical conductivity structure beneath the contiguous US, in preparation
- Munch, F. and Grayver, A., (2023). Multi-scale imaging of 3-D electrical conductivity structure under the contiguous US constrains lateral variations in the upper mantle water content, Earth and Planetary Science Letters. https://doi.org/10.1016/j.epsl.2022.117939
