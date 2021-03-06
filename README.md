SCAPE Characterisation Components Benchmarking Data
===================================================

Holds machine readable test data for the initial SCAPE Characterisation Components 

Overview
--------

* title: SCAPE Characterisation Components Benchmarking Data
* creator-name: SCAPE Project
* creator-url: http://scape-project.eu
* dataset-url (text/csv): https://raw.github.com/openplanets/cc-benchmark-tests/master/tika-1.2-test.csv
* dataset-url (application/json): https://raw.github.com/openplanets/cc-benchmark-tests/master/tika-1.2-test.json
* original format: text/csv

Data Release Type
-----------------

- [] a one-off release of a single dataset
- [x] a one-off release of a set of related datasets
- [] ongoing release of a series of related datasets
- [] a service or API for accessing open data

Dataset Type 
--------------------

- [] human-readable documents
- [x] statistical data, such as counts, averages and percentages
- [] geographic information, such as points and boundaries
- [] other kinds of structured data

Description
-----------

A record of Tika identification results and benchmark timing, tested on the GovDocs corpora.
There are 8 result files, two for each of the four versions of Tika that were evaluated, 1.0, 1.1, 1.2 and 1.3.

The following four files include the evaluation results obtained when calling Tika using a file input stream only, i.e. no file name
  Tika_1_0.csv - Evaluation results when using Tika v1.0 
  Tika_1_1.csv - Evaluation results when using Tika v1.1 
  Tika_1_2.csv - Evaluation results when using Tika v1.2 
  Tika_1_3.csv - Evaluation results when using Tika v1.3 

The following four files include the result when calling Tika using 
a file input stream and also a file name
  Tika_1_0_with_filename.csv - Evaluation results when using Tika v1.0 
  Tika_1_0_with_filename.csv - Evaluation results when using Tika v1.1 
  Tika_1_0_with_filename.csv - Evaluation results when using Tika v1.2 
  Tika_1_0_with_filename.csv - Evaluation results when using Tika v1.3 

The data is in CSV format, each record consists of five fields:

1. the name of the input file
2. the MIME type returned by Tika
3. the MIME type(s) from the GovDocs groundtruth (separated with semi colons)
4. time in milliseconds taken to perform Tika identification
5. boolean OK/FAIL indicating whether Tika successfully identified the file type

Copyright & License
-------------------

All content and data are © 2013 [Scape Project](http://www.scape-project.eu/) and licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/deed.en_GB).

Open Data
---------

All data in this dataset is released at Open Data. It is available freely for anyone to use, re-use and re-distribute subject only to the requirements set out in the license. These requirements stipulate that you must attribute our data in your work AND share the resulting works under a similar license. 

This dataset has been self assessed to be of "3-Star" quality (see [5 Star Data](http://5stardata.info)) and compatible with the "Pilot Level" requirements of the [Open Data Institutes](http://www.theodi.org) [Open Data Certificate](https://github.com/theodi/open-data-certificate). 

Personally Identifiable Data 
----------------------------

This dataset does not contain any personally identifiable data other than that relating to the curators, maintainers and publishers of the dataset and related information.

Using the Data
--------------
The CSV (text/csv) file can be opened in Excel and other spreadsheet applications.

Both CSV and JSON are machine readable formats and more information about each can be found at the following locations:

CSV: http://en.wikipedia.org/wiki/Comma-separated_values 
JSON: http://en.wikipedia.org/wiki/JSON

Findability
-----------

- [] Data can be found within 3 clicks of the organisation's home page
- [] Is the data listed somewhere, alongside data from the wider sector

Applicability
-------------

This dataset does not contain any time sensitive information

Quality
-------

* Issues : https://github.com/openplanets/cc-benchmark-tests/issues
* Policy : 

Guarantees
----------
This data is available experimentally but should be around until July 2014

References
-------------

- [] Do the data formats use vocabularies?
- [*] Are there any codes used within the data?

MIME Types are used within the dataset, e.g. text/csv. A list of IANA MIME types is available at http://www.iana.org/assignments/media-types.

The File name field relates to the name of the file within the GovDocs dataset, available at http://digitalcorpora.org/corpora/files. 

Support
-------

contact: carl@openplanetsfoundation.org

We're currently not supporting a mailing list or forum for discussion of this dataset.
Problems can be logged at the projects issue page: https://github.com/openplanets/cc-benchmark-tests/issues

Services
--------

Links to tools for working with this data:t 

