# Planck Distribution Integrals

This repo currently contains one Jupyter notebook written to address the following task:

> Generate a table of values that integrate Planck's distribution numerically from frequency 0 to each of 1024 optical frequencies in Hz from a Jaz™ spectrometer wavelength file. (provided, second column is frequency in Hz).. Integral values are to be 24 digits accurate with a maximum round-off of ±1 in the 25th digit. There shall be two versions of this table, one for temperature 6007 [K], and another for 5077 [K]. The output file format is space delimited tables with first column being frequency in Hz, integration value in the second column with units as a string " [ W/m² ] / [ Sr ]" in third column, The first line of the file should contain an additional benchmark integration from 0 [Hz] to whatever the peak density frequency of the Planck distribution is for the temperature given, The first line needs to have an extra fourth column that contains the temperature of the list, or else the filename if the work product must indicate the kelvin temperature.. The work product shall be delivered as two ascii or utf-8 text files. Each file should contain data for only a single temperature.

See [NumericalBenchmarks.ipynb](./NumericalBenchmarks.ipynb) for the code.

Click the following badge to open the notebook in your browser using Google CoLab.
<a href="https://colab.research.google.com/github/OliverEvans96/planck-integral/blob/main/NumericalBenchmarks.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

See the [outputs directory](./outputs) for the final results.
