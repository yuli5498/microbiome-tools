#Using the uBiome Tools Repository

![logo](./docs/images/uBiome Logo 480.png)

Please add your tools here, and edit this file to keep a directory of scripts, programs, templates, or anything else you find useful for manipulating or analyzing uBiome information.

**[ubiome.py: Python module](./docs/compareSamplesPython.md)** Compare any two uBiome samples to find unique taxa (bacteria) or to show the difference in counts. If you have a Mac, the script works without installing anything else.


**[RuBiome: simple scripts in R](./docs/RuBiomeTools.md)**


* [__uBiome_compare_samples__](./docs/compareSamples.md)
Given two samples, output all the differences, including the difference in count_norm

* [__uBiome_sample_unique__](./docs/findUnique.md)
Given two samples, output which rows are the uniquely found in one but not the other.

* [__convert_json_files_to_csv__](./docs/convertJsonToCSV.md) Convert all JSON files in a
directory to CSV files, suitable for reading in Excel or use with the other functions here.

**[uBiome JSON to D3 Tree Graph](https://github.com/jrrera/ubiome-to-d3)** A lightweight
JavaScript library that generates an interactive D3 tree visualization from
your uBiome JSON data.