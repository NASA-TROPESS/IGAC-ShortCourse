# IGAC-ShortCourse
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/NASA-TROPESS/IGAC-ShortCourse/blob/main/LICENSE.txt)

This repo intends to provide curated set of Jupyter Python notebooks for the IGAC Short Course. 

The notebooks feature the following capabilities:
1. Data search/discovery
2. Data access/subset/extraction
3. Data plotting/analysis/visualization

## Special Notes for First-Time Users:
1. See the **[environment.yml](https://github.com/NASA-TROPESS/IGAC-ShortCourse/blob/main/environment.yml)** file for a list of dependencies.
2. If you not familiar with managing your own dependencies, we suggest utilizing the provided **[environment.yml](https://github.com/NASA-TROPESS/IGAC-ShortCourse/blob/main/environment.yml)** file, as follows:
   
  **Step 1:** Create a new conda environment called tropess-igac-env:
  
   -> Download the **[environment.yml](https://github.com/NASA-TROPESS/IGAC-ShortCourse/blob/main/environment.yml)** file.
   
   -> Install the free "mini" conda package: **[https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)**
   
   -> Run the following from your commandline: **conda env create --file environment.yml**
   
      
  **Step 2:** Initialize your new "tropess-igac-env" environemnt:
  
   -> Run the following from your commandline: **conda activate tropess-igac-env**
   
   
## Tutorial Summary
| Notebook Title    | Summary        | Link        | Features/Capabilities |
|-------------------|----------------|-------------|-----------------------|
| TROPESS Demonstration of Ozone Data from CrIS and OMI Satellite Instruments - **Integrated Data Download** | A Jupyter Notebook coded in Python which demonstrates how to open TROPESS CrIS and OMI Ozone data, manipulate the data, and make figures including time series, maps, and atmospheric profiles over a 2-week analysis period. | **[Notebook](https://github.com/NASA-TROPESS/IGAC-ShortCourse/blob/main/IGAC2024_TROPESS_cris_omi_ozone_demo_integrated_download.ipynb)** <br /> <br /> [![Binder](https://mybinder.org/badge_logo.svg)<img  width="400">](https://mybinder.org/v2/gh/NASA-TROPESS/binders/8f2606f23d651ac0f38882d440124d7f0a73d0a8?urlpath=lab%2Ftree%2FIGAC2024_TROPESS_cris_omi_ozone_demo_integrated_download_4binder.ipynb) | Data access/subset/extraction/plotting/analysis/visualization |
| Study of the 2020 COVID Lockdown (February-July) using the TROPESS Chemical Reanalysis (TCR) Version 2 Download and Analysis Notebook - **Integrated Data Download** | A Jupyter Notebook coded in Python which reads the TROPESS Chemical Reanalysis Surface Total NOx emissions Monthly 2-dimensional Product V1 (TRPSCRENOXTM2D) data products for February to July 2020 directly using HTTPS-based download from NASA Earthdata (GES DISC) and makes a monthly data plots for monthly comparison. | **[Notebook](https://github.com/NASA-TROPESS/IGAC-ShortCourse/blob/main/study-2020-covid-lockdown-tcr2-igac.ipynb)** <br /> <br /> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NASA-TROPESS/binders/c8c588d306615d8588b208bc2a95dac035a1044a?urlpath=lab%2Ftree%2Fstudy-2020-covid-lockdown-tcr2-download-analysis_4binder.ipynb) | Data access/subset/extraction/plotting/analysis/visualization | 
| Study 2023 Canadian Wildfires using TROPESS CrIS JPSS-1 Carbon Monoxide (CO) data products - **Integrated Data Download** | A Jupyter Notebook coded in Python which reads TROPESS CrIS JPSS-1 CO data products for June 2023 and June 2022 and makes a monthly averaged data product and plots and compare them with fully integrated download of the input data files. | **[Notebook](https://github.com/NASA-TROPESS/IGAC-ShortCourse/blob/main/study-2023-canadian-wildfire-effect-igac.ipynb)** <br /> <br /> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NASA-TROPESS/binders/b66bf7208d615e8673ba2a42af7aad744cec6886?urlpath=lab%2Ftree%2Fstudy-2023-canadian-wildfire-effect-integrated_data_download_4binder.ipynb) | Data access/subset/extraction/plotting/analysis/visualization | 

## Copyright and Licensing Info
Copyright (c) 2023-24 California Institute of Technology (“Caltech”). U.S. Government sponsorship acknowledged. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided
that the following conditions are met:

• Redistributions of source code must retain the above copyright notice, this list of conditions and
the following disclaimer.

• Redistributions in binary form must reproduce the above copyright notice, this list of conditions
and the following disclaimer in the documentation and/or other materials provided with the
distribution.

• Neither the name of Caltech nor its operating division, the Jet Propulsion Laboratory, nor the
names of its contributors may be used to endorse or promote products derived from this software
without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS
IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Open Source License Approved by Caltech/JPL
APACHE LICENSE, VERSION 2.0
• Text version: https://www.apache.org/licenses/LICENSE-2.0.txt
• SPDX short identifier: Apache-2.0
• OSI Approved License: https://opensource.org/licenses/Apache-2.0
