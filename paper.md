---
title: 'EDDS: A Python Package for Accessing Turkish Economic Data'
tags:
  - Python
  - economy
  - data processing
  - Turkish economy
  - API
authors:
  - name: Altan Alaybeyoğlu
    orcid: 0000-0001-6309-0697
    affiliation: 1
affiliations:
 - name: Haliç University, Turkey
   index: 1
date: 18 September 2024
bibliography: paper.bib
---

# Summary

Accessing reliable economic data is a fundamental challenge for researchers, especially when focusing on developing countries. The **Electronic Data Distribution System (EDDS)**, provided by the Central Bank of the Republic of Turkey, offers various economic datasets. However, accessing these datasets manually can be complex and time-consuming. To address this issue, we developed `edds`, a Python package that simplifies access to Turkish economic data, automating data retrieval and preparation.

# Statement of Need

Researchers analyzing the Turkish economy need reliable and well-structured data. However, manual data collection is tedious and prone to errors. `edds` provides a simple interface for interacting with the EDDS API, enabling users to access and format data efficiently. The package allows researchers to focus on analysis rather than time-consuming data preparation tasks, contributing to the productivity of economic research.

# Features

- Automated access to Turkish economic data through the EDDS API.
- Data cleaning and formatting tools.
- Integration with popular data analysis libraries like `pandas`.
- Open-source and easy-to-use interface, suitable for academic and professional research.

# Acknowledgements

We would like to thank the Central Bank of the Republic of Turkey for making their data publicly accessible through EDDS and acknowledge the support from Haliç University.

# References

@article{Mongeon:2016,
  author = {Mongeon, P. and Paul-Hus, A.},
  title = {The journal coverage of Web of Science and Scopus: A comparative analysis},
  journal = {Scientometrics},
  volume = {106},
  pages = {213-228},
  year = {2016},
  doi = {10.1007/s11192-015-1765-5}
}

@misc{Alaybeyoglu:2024,
  author = {Alaybeyoğlu, Altan},
  title = {edds: The Central Bank of the Republic of Türkiye Electronic Data Distribution System Data Access Package},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  url = {https://github.com/altanalaybeyoglu/edds}
}
