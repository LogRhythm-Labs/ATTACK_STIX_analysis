ATT&CK_STIX_analysis

This repository is a collection of Jupyter notebooks exploring usage of the attackcti Python library (https://pypi.org/project/attackcti/) to interact with the MITRE ATT&CK Framework (https://attack.mitre.org/)

Requirements:

- Some way to run Jupyter notebooks, such as Microsoft Visual Studio Code (https://code.visualstudio.com/) or JupyterHub (https://jupyter.org/hub)

There are several Python libraries that will need to be installed via something like pip (e.g "pip install attackcti"):

attackcti
requests
json
pandas 
numpy
xlsxwriter

Included notebooks are:

MITRE_STIX_TAXII_exploration.ipynb - this is an introduction to loading the MITRE ATT&CK Enterprise Matrix and accessing the information within.
ConvertATT&CK_v6_to_v7.ipynb - this notebook will take a list of version 6 MITRE ATT&CK techniques and convert them to version 7 (the version with which subtechniques were intoduced)
Prepare_technique_data_for_Excel.ipynb - this notebook will take a list of MITRE ATT&CK techniques (they should be version 7 techniques) and produce an Excel workbook containing tabs with the data source requirements, platform requirements and tactics for each technique.