# Placeholder

# Contents
This directory contains the data required for the OmdenaAI Karimganj Assam Chapter Flood Prediction and Management project.

It includes historical climate data for 10 years from the Karimganj district of Assam.

This consist of various fields such as 
time	temperature_2m (Â°C)	relative_humidity_2m (%)	dew_point_2m (Â°C)	precipitation (mm)	rain (mm)	pressure_msl (hPa)	surface_pressure (hPa)	cloud_cover (%)	cloud_cover_low (%)	cloud_cover_mid (%)	cloud_cover_high (%)	et0_fao_evapotranspiration (mm)	vapour_pressure_deficit (kPa)	wind_speed_10m (m/s)	wind_speed_100m (m/s)	wind_direction_10m (Â°)	wind_direction_100m (Â°)	wind_gusts_10m (m/s)	soil_temperature_0_to_7cm (Â°C)	soil_temperature_7_to_28cm (Â°C)	soil_temperature_28_to_100cm (Â°C)	soil_temperature_100_to_255cm (Â°C)	soil_moisture_0_to_7cm (mÂ³/mÂ³)	soil_moisture_7_to_28cm (mÂ³/mÂ³)	soil_moisture_28_to_100cm (mÂ³/mÂ³)	soil_moisture_100_to_255cm (mÂ³/mÂ³)
revier discharges 
## Pulling Changes from the Main Branch

To pull changes from the main branch of the original repository into your fork, follow these steps:

1. **Ensure the original repository is added as a remote**:
  ```bash
  git remote -v
  ```
  If the original repository is not listed, add it:
  ```bash
  git remote add upstream https://github.com/ORIGINAL_OWNER/REPO_NAME.git
  ```

2. **Fetch the latest changes from the main branch of the original repository**:
  ```bash
  git fetch upstream
  ```

3. **Merge the changes into your working branch**:
  ```bash
  git checkout YOUR_WORKING_BRANCH
  git merge upstream/main
  ```

4. **Resolve any merge conflicts if they arise**:
  Open the conflicting files, resolve the conflicts, and then:
  ```bash
  git add .
  git commit
  ```

5. **Push the updated branch to your forked repository**:
  ```bash
  git push origin YOUR_WORKING_BRANCH
  ```

Replace `ORIGINAL_OWNER`, `REPO_NAME`, and `YOUR_WORKING_BRANCH` with the appropriate values for your repository and branch.

# Motivation
The motive behind this data collection is to create a predictive model for flood prediction based on past data.



## Data Source and License

The data used in this project is sourced from [open-meteo.com/](hhttps://open-meteo.com/). The data is licensed under the [CC-BY-4.0](https://github.com/open-meteo/open-meteo/blob/main/LICENSE).

@software{Zippenfenig_Open-Meteo,
  author = {Zippenfenig, Patrick},
  doi = {10.5281/zenodo.7970649},
  license = {CC-BY-4.0},
  title = {Open-Meteo.com Weather API},
  year = {2023},
  copyright = {Creative Commons Attribution 4.0 International},
  url = {https://open-meteo.com/}
}
## Syncing with the Main Branch

If you have forked a repository and want to pull changes from the main branch of the original repository, follow these steps:

1. **Add the original repository as a remote**:
  ```bash
  git remote add upstream https://github.com/ORIGINAL_OWNER/REPO_NAME.git
  ```

2. **Fetch the latest changes from the main branch of the original repository**:
  ```bash
  git fetch upstream
  ```

3. **Merge the changes into your local branch**:
  ```bash
  git checkout main
  git merge upstream/main
  ```

4. **Push the updated main branch to your forked repository**:
  ```bash
  git push origin main
  ```

Replace `ORIGINAL_OWNER` and `REPO_NAME` with the appropriate values for the original repository.

This ensures your fork stays up-to-date with the main branch of the original repository.