# CellBarcoding2023_Maurer
"Barcoding" and tracking individual cells using optically addressable quantum sensors. For more introduction of the project, see its [project page](https://jhanliufu.github.io/projects/cell_tracking.html) on Jhan's website.

- **[ND_orientation_calculation_8_peak_Lorentzian_fit.ipynb](ND_orientation_calculation_8_peak_Lorentzian_fit.ipynb)** demonstrates resolving the spatial orientation of nanodiamonds with four nitrogen-vacancy (NV) centers. The orientation can be uniquely determined using Lorentzian fitting.

- **[Angle_resolution_algorithm_2NVs_on_each_ND.ipynb](Angle_resolution_algorithm_2NVs_on_each_ND.ipynb)** demonstrates resolving the **relative** angle between two nanodiamonds, each having two NV centers. The relative angle can be uniquely determined.

- **[Angle_resolution_algorithm_1NVs_on_each_ND.ipynb](Angle_resolution_algorithm_1NVs_on_each_ND.ipynb)** and **[1_1_NV_angle_spectrum_calculation.ipynb](1_1_NV_angle_spectrum_calculation.ipynb)** demonstrates estimating the **relative** angle between two nanodiamonds, each having one NV center. The angle can not be uniquely resolved with only one NV center, so the algorithm involves calculating and updating a distribution of possible relative angles bewteen two NVs. With more measurments, the distribution mean approaches the true relative angle, and the distribution variance decreases.
