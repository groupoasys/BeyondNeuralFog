# BeyondNeuralFog

The aim of this repository is to provide details of the data sets and code used in the related research titled *Beyond the Neural Fog: Interpretable Learning for AC Optimal Power Flow* ([Link to paper](https://arxiv.org/pdf/2408.05228)).

## Data Description

The following files are included in this repository:
* `case14.m`: MATPOWER file containing data for the IEEE 14-bus power system.
* `case30.m`: MATPOWER file containing data for the IEEE 30-bus power system.
* `case57.m`: MATPOWER file containing data for the IEEE 57-bus power system.
* `case118.m`: MATPOWER file containing data for the IEEE 118-bus power system.

We have used the dataset from Joswig-Jones, Trager, Ahmed Zamzam, and Kyri Baker. 2021. "OPFLearnData: Dataset for Learning AC Optimal Power Flow." NREL Data Catalog. Golden, CO: National Renewable Energy Laboratory. Last updated: January 21, 2025. DOI: 10.7799/1827404. In particular:
* `opflearn_case14_IEEE`: [pglib_opf_case14_ieee.csv](https://data.nrel.gov/system/files/177/pglib_opf_case14_ieee.csv)
* `opflearn_case30_IEEE`: [pglib_opf_case30_ieee.csv](https://data.nrel.gov/system/files/177/pglib_opf_case30_ieee.csv)
* `opflearn_case57_IEEE`: [pglib_opf_case57_ieee.csv](https://data.nrel.gov/system/files/177/pglib_opf_case57_ieee.csv)
* `opflearn_case118_IEEE`: [pglib_opf_case118_ieee.csv](https://data.nrel.gov/system/files/177/pglib_opf_case118_ieee.csv)

## References

[1] {{ Reference_1_Details }}

## Developed by

* S. Pineda ([spineda@uma.es](mailto:spineda@uma.es)) - [GitHub: salvapineda](https://github.com/salvapineda)  
* Juan Pérez ([jperez@uma.es](mailto:jperez@uma.es))  
* J.M. Morales ([juan.morales@uma.es](mailto:juan.morales@uma.es)) - [GitHub: Juanmi82mg](https://github.com/Juanmi82mg)  

## Funding

This work was supported by the Spanish Ministry of Science and Innovation (AEI/10.13039/501100011033) through projects:
  * PID2020-115460GB-I00  
  * PID2023-148291NB-I00  

## How to cite the repo and the paper?

If you want to cite the related paper or this repository, please use the following bib entries:

* Article:
```
@article{{ {{ Article_Citation_Key }},
title = {{ {{ Article_Title }} }},
journal = {{ {{ Journal_Name }} }},
volume = {{ {{ Volume }} }},
pages = {{ {{ Pages }} }},
year = {{ {{ Year }} }},
author = {{ {{ Authors }} }}
}
```
* Repository:
```
@misc{{BeyondNeuralFog,
author = {S. Pineda and J. Pérez and J.M. Morales},
year = {2024},
title = {BeyondNeuralFog},
howpublished = {\url{https://github.com/groupoasys/BeyondNeuralFog}}
}
```

## Do you want to contribute?

Please, do it. Any feedback is welcome, so feel free to ask or comment anything you want via a Pull Request in this repo.  
If you need extra help, you can contact us.

## License

Licensed under the GNU General Public License, Version 3 (the "License");  
you may not use this file except in compliance with the License.  
You may obtain a copy of the License at:

   http://www.gnu.org/licenses/gpl-3.0.en.html

Unless required by applicable law or agreed to in writing, software  
distributed under the License is distributed on an "AS IS" BASIS,  
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  
See the License for the License governing permissions and  
limitations under the License.


