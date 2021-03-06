This repository depends on the [EarthArXiv API repo](https://github.com/eartharxiv/API.git), which is included as a Git submodule. You should first consult the README for that module as API calls require creation of an API token. 

The analysis code in this repo is
* eartharxiv_papers_per_week.py - queries the API and outputs number of papers submitted by week
* parseLog.py - parses and summarizes the log file created by the EarthArXiv API repo code
* keywordsOverTime.py - parses log file from parseLog.py to compute monthly usage of keywords
* keywordsOverTimeSpecificValue.py - parses log files from parseLog.py to find a specific keyword and output its usage over time


Version 2.1, [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3204815.svg)](https://doi.org/10.5281/zenodo.3204815)

Version 2.0, [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2649580.svg)](https://doi.org/10.5281/zenodo.2649580)  
Version 2.0 dataset, https://doi.org/10.6084/m9.figshare.8030819.v1

Version 1.0, [![DOI](https://zenodo.org/badge/153806329.svg)](https://zenodo.org/badge/latestdoi/153806329)
