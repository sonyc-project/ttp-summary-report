# Home Sensor Deployment - User Report
As part of the SONYC Home Deployment series (Summer 2022), we aim to deliver participants a comprehensive user report on their deployment. 

## About the Report
This report analyzes SPL and ML data from recorded audio & app usage data over the course of a participant's deployment, pulling out key findings, noise patterns, and additional trends. 

## Components
#### 1 - plots.ipynb

  - takes in participant .csv files from their deployment and analyzes SPL levels, computes metrics, and creates data visualizations. Exports plots to /plotimg

#### 2 - plotimg folder

  - holds image contents exported from plots.ipynb

#### 3 - template.pptx

  - template powerpoint of user report, includes placeholders
  
#### 4 - python2pptx.ipynb

  - creates new user report, replaces placeholders with plots using template.pptx and /plotimg


## Dependencies
- [sonycctl](https://github.com/sonyc-project/sonycctl/tree/main/sonycctl) -- click link for installation details

Packages
  ```
  python -m pip install [package name]
  ```
 - numpy
 - pandas
 - python-pptx
 - pprint
 - datetime
  
