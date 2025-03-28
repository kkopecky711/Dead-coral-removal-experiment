# Dead-coral-removal-experiment

Code and datafiles for experiment involving the effects of removing dead coral on the growth and survival of live coral, as well as development of macroalgae. The experiment was conducted in Moorea, French Polynesia from 2019 - 2023, following a major coral bleaching event in April 2019. The code contained here was used to generate analyses and figures for a published dissertation chapter and manuscript in prep entitled "Clearing a path to resilience: removal of dead coral mitigates downstream impacts of coral bleaching".

In the "Data" folder, there are three main data files that were used for analyses in the above mentioned manuscript:
- [Regions_master.csv](https://github.com/kkopecky711/Dead-coral-removal-experiment/blob/main/Data/Regions_master.csv) is a data file generated from the image segmentation software, [TagLab](https://github.com/cnr-isti-vclab/TagLab), that includes vector data (perimeter, planar area, 3D surface area, and pixel coordinates for the centroids of each object) of live and dead branching coral colonies measured within photomoasics of ~4m^2 experimental plots that either had dead coral skeletons initially removed or left in place after the coral bleahcing event. This data file contains these vetor data for coral colonies in 20 experimental plots in each of four years from 2019-2023.

Experimental plot with corals measured in TagLab. ![Screen Shot 2023-02-21 at 5 25 53 PM](https://github.com/user-attachments/assets/adbcf19c-7a55-47db-8f3c-eb4ce506966a)

- [Algae point data.csv](https://github.com/kkopecky711/Dead-coral-removal-experiment/blob/main/Data/Algae%20point%20data.csv) is a datafile also generated from TagLab with point count data for various taxa of macroalgae. For each plot in each year, a grid of points was ovelaid on the photomosaic, and each point was classified as either a type of macroalgae or 'other' (because corals were measured using image segmentation described above). Further, we recorded when points fell within regions annotated (segmented) as dead coral to evaluate the degree to which macroalgae grew on dead coral as a substrate.  

-  [Recruit-counts_2023.csv](https://github.com/kkopecky711/Dead-coral-removal-experiment/blob/main/Data/Recruit-counts_2023.csv) is a dataset of visual counts of coral recruit in 2023 inside the experimental plots. These counts were done in situ (on SCUBA), as the resolution of our photomosaics did not enable us to reliably detect corals of this size. We recorded the size, taxa, and substrate that each coral recruit was found on in each of the 20 experimental plots.

[![DOI](https://zenodo.org/badge/790458907.svg)](https://zenodo.org/doi/10.5281/zenodo.13742953)
