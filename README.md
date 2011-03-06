Lists Of Values
===============

How many times you have been writing an application and needed a list of countries, areas, provinces, counties, phone prefixes, postal codes, etc. and you had to search for it with not so successful results?

LOVS repository is intended to be a collaborative effort to provide a central place to find lists of values of common use accross applications.

Organization
------------

The files are stored in ISO 639-1 code language folders and a subfolder with language code + ISO 3166-1 country code will exists if the file is more country specific.

Datasets with no language or not applicable will fall in the universal folder.

Format
------

All lists are valid JSON YAML. This means that it's format is YAML files compatible with JSON syntax and should be parseable by YAML modules like Syck.


How to contribute
-----------------

  * Be sure that your dataset it's not already in the repository to not duplicate data.

  * Be sure your files validates. You can use this tool: http://www.jslint.com/ or http://jsonformatter.curiousconcept.com/

  * Fork the repository

  * Add your files to it
  
  * Test it with the test script and check if the test passes.

  * Send us a pull request, one file per pull request, one pull request per file.

Tip: You can find useful datasets spread all over the web.

Testing your files
------------------

Use 

    script/test -- [File]

to test your files
