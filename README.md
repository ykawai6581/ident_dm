# ident-dm

### 📄 `sample_planets.csv`

This file contains the complete list of exoplanets analyzed in Kawai+2025 (under review), with key stellar and planetary parameters relevant in the study. The table is based on default parameters obtained from NASA Explanet archive as of May 22, 2025. From there, mass and eccentricity are updated for planets in Bonomo+2017, obliquity is updated for planets in Albrecht+2022 and Kundstrup+2025. Eccentricity of planets with assumed circular orbits are replaced with their upper limits when they are reported in the respective discovery papers. Errors for all parameters can be accessed with "err1" (upper) and "err2" (lower), as in NASA Exoplanet Archive.

#### Included Columns (`params_included`):

| Column Name                         | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| `pl_name`                          | Planet name (e.g., WASP-12b)                                               |
| `hostname`                         | Host star name                                                             |
| `hostname_omit_binary_signature`  | Host star name with binary suffixes (e.g., "A", "B") removed               |
| `sy_pnum`                          | Number of planets in the system                                            |
| `sy_vmag`                          | Host star V-band magnitude                                                 |
| `circularization_timescale`       | Tidal circularization timescale (in Gyr)                                   |
| `st_age`                           | Stellar age (in Gyr)                                                       |
| `tau_over_age`                     | Circularization timescale over stellar age:  |
| `pl_orbeccen`                      | Orbital eccentricity of the planet                                         |
| `pl_orbeccenlim`                   | Eccentricity upper limit flag (True/False)                                 |
| `st_mass`                          | Stellar mass (in solar masses)                                             |
| `st_teff`                          | Stellar effective temperature (in Kelvin)                                  |
| `st_rad`                           | Stellar radius (in solar radii)                                            |
| `st_met`                           | Stellar metallicity                                                        |
| `pl_mass_combinej`                 | Combined estimate of planet mass (in Jupiter masses)                       |
| `pl_massj`                         | Planet mass from one source (in Jupiter masses)                            |
| `pl_radj`                          | Planet radius (in Jupiter radii)                                           |
| `pl_orbper`                        | Orbital period (in days)                                                   |
| `pl_orbsmax`                       | Semi-major axis (in AU)                                                    |
| `pl_ratdor`                        | Scaled semi-major axis (i.e., \( a/R_\star \))                             |
| `pl_dens`                          | Planet density (in g/cm³)                                                  |
| `lambda`                      | Projected spin-orbit angle \( \lambda \) (in degrees)                      |
| `mass_ratio`                       | Planet-star mass ratio \( q = M_p / M_\star \)                             |
