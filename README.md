# Cui-2025-WRR-fish-strategies-spectrum-data
Data and materials for the manuscript: "A capability-driven spectrum of hydrodynamic strategies in a fish community
# Data for: A capability-driven spectrum of hydrodynamic strategies in a fish community

This repository contains the processed data for the manuscript titled "A capability-driven spectrum of hydrodynamic strategies in a fish community".

The data herein includes the processed kinematic and spatial position datasets for the four fish species studied: *Onychostoma sima*, *Acrossocheilus monticolus*, *Procypris rabaudi*, and *Acrossocheilus yunnanensis*. This data was used to generate the figures and perform the statistical analyses presented in the paper.

## Citation

If you use this dataset in your research, please cite both the original manuscript and the dataset itself.

**Manuscript Citation:**

> **[Complete citation format after formal publication of the paper]**

**Dataset Citation (Zenodo):**

> **[这里将来粘贴您从Zenodo获得的DOI引用格式]**

## Dataset Description

The data is provided in `.csv` format. Each file corresponds to a specific fish species and contains time-series data of its location and calculated kinematic parameters under various flow conditions.

### File Structure

The repository is organized as follows:

-   `Onychostoma_sima_data.csv`: Processed data for *Onychostoma sima*.
-   `Acrossocheilus_monticolus_data.csv`: Processed data for *Acrossocheilus monticolus*.
-   `Procypris_rabaudi_data.csv`: Processed data for *Procypris rabaudi*.
-   `Acrossocheilus_yunnanensis_data.csv`: Processed data for *Acrossocheilus yunnanensis*.

### Column Headers


Each .csv file contains the following columns, representing the kinematic data extracted for each frame of the experimental video:

-   "Frame": The frame number of the video sequence.
-   "Centroid_X_m": The x-coordinate (streamwise) of the fish's center of mass, in meters.
-   "Centroid_Y_m": The absolute x-coordinate (streamwise) of the fish centroid, in meters.
-   "Head_X_m": The x-coordinate of the fish's head (e.g., snout tip), in meters.
-   "Head_Y_m": The y-coordinate of the fish's head, in meters.
-   "Tail_X_m": The x-coordinate of the fish's tail tip, in meters.
-   "Tail_Y_m": The y-coordinate of the fish's tail tip, in meters.
-   "Head_Angle_deg": The oscillation angle of the head relative to the body's mean path, in degrees.
-   "Tail_Angle_deg": The tail-beat angle (α) relative to the body's longitudinal axis, in degrees.
-   "Head_Amplitude_m": The lateral oscillation amplitude of the head, in meters.
-   "Tail_amplitude_m": The tail-beat amplitude (a), defined as the maximum lateral excursion of the tail tip, in meters.
-   "Frequency_hz": The calculated tail-beat frequency (f) for the time window surrounding this frame, in Hertz.

## Contact

For any questions regarding the dataset, please contact **[Shihao Cui]** at **[csh95dy42@163.com]**.
