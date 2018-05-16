# Montana banks PDF duder

A [Jupyter notebook](https://github.com/cjwinchester/mt-banks-pdf-duder/blob/master/Montana%20bank%20list.ipynb) demonstrating how to use [pdfplumber](https://github.com/jsvine/pdfplumber) to extract data from a PDF.

We'll parse a [short PDF](http://banking.mt.gov/Portals/58/Bank_List.pdf) of state-chartered banks in Montana and flatten the data so that one record = one branch, then write out to [a JSON file](https://github.com/cjwinchester/mt-banks-pdf-duder/blob/master/mtbanks.json).