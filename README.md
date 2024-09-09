> [!WARNING]
> **This repository is no longer being developed - see John Handley's [Travel to work area algorithm in Rust](https://github.com/jwhandley/ttwa-detection) repository for the TTWA algorithm.**

#  Travel to Work Areas
The purpose of this repository is to provide a transparent process for generating UK Census Travel to Work Areas (TTWAs) based on the Office for National Statistics (ONS) and Newcastle University methodology [used to generate the 2011 TTWAs](https://geoportal.statistics.gov.uk/datasets/ons::travel-to-work-areas-2011-guidance-and-information/about).

## Algorithm
![image](https://github.com/thomashudsonuk/ttwa/assets/5777564/844c5d07-9616-4484-ae83-4fccf2336a54)
From page 14 of [Travel-to-Work Areas: the 2007 review](https://www.ncl.ac.uk/media/wwwnclacuk/curds/files/TTWA%20report.pdf).

## Data
- Commute matrix (for example the 2021 [estimation of travel to work matrices in England and Wales](https://www.ons.gov.uk/releases/estimationoftraveltoworkmatricesenglandandwales)).
- Polygons for zones (for example [Middle Layer Super Output Areas (2021) Boundaries EW BSC](https://geoportal.statistics.gov.uk/search?collection=Dataset&sort=name&tags=all(BDY_MSOA%2CDEC_2021))).
