# Web Scraping with ShipInfo data

The **Web-Scraping-ShipInfo** module consists of a python-based Jupyter-notebook 
designed to demonstrate the use of web scraping techniques to get Ship Details, such as Name, IMO, MMSI or Type, from the [ShipInfo Website](https://shipinfo.net) to be able to cross check another source of information. For instance, it could be used to merge the fleet of any Shipping company and see more details regarding a specific ship. The case here has implemented a fleet of a Norwegian company to extract IMO number and MMSI from the ShipInfo dataset.


The idea behind this code is to obtain as much information as possible while one is working with AIS data, data which usually some values are missed and it should be a nice procedure to compare with other sources of information.  

Before running the code, recommended to check the ShipInfo website and its html to be familiarize with the web scraping process. Run each cell one by one to get results. Additionally, the user can increase the quantity of pages it is desired, but the longer it is, the more time it will take the code to finish. 

For any questions about this repository, please contact me via juan.fernandez.sea@gmail.com

## Authors

* [**Juan Fernandez**](mailto://juan.fernandez.sea@gmail.com) - [Linkedin](https://www.linkedin.com/in/juan-fernandez-martinez/)



## Prerequisites

You will require `Jupyter Notebook` to run this code. We recommend that you install 
the latest [Anaconda Python distribution](https://www.anaconda.com/) for your 
operating system. Anaconda Python distributions include Jupyter Notebook.


This collection supports Python 3.10. Although many options are possible, the 
authors highly recommend that users install the appropriate Anaconda package 
for their operating system. In order to ensure that you have all the required 
dependencies, we recommend that you build a suitable Python environment, as 
discussed below.


## Dependencies

|item|version|licence|package info|
|---|---|---|---|
|python|3.10.13|PSF|https://docs.python.org/3/license.html|
|matplotlib|3.8.3|PSFL|https://matplotlib.org/stable/users/project/license.html|
|beautifulsoup4|4.12.3|MIT|https://pypi.org/project/beautifulsoup4/|
|pandas|2.2.1|BSD-3|https://pandas.pydata.org|
|numpy|1.3.0|BSD-3|https://numpy.org/doc/stable/index.html|







