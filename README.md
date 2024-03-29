# airQuality ☁

## Data gathering
We consider using open data to obtain all the data required to develop a consistent and coherent 
analysis of the quality air.

We find different platforms to obtain the data. The main idea was to join all the data to get more exhaustive information to analyse and finally obtain better results. However, we find that the platforms
considered, use different types to provide the data for example JSON, CSV and others. Also, the big problem was when the models to represent the data are different between platforms and in some cases, we don't have useful data such as our country. It means that we don't have homogeneous data, and the possibility to harmonization all the data could be difficult and take expensive time. 

Finally, we consider to use OpenAQ to get all the data used to develop the analysis, it is because it has a lot of datasets from different countries and in some cases it has the same data from other platforms. In addition, it has different ways to obtain the data for example:
OpenAQ API, download the datasets from specific country or use a web client to download the data.

In order to get the data we create a script called get_data.py that request the data to the OpenAQ API and save it in the local machine.
## Data cleaning
As we can see on the jupyter notebooks called "Clean Air Quality" the data provided by OpenAQ API don't have errors, empty values, suspicious outliers or data types problems, the data provided has a well model and it is easy to understand. 
In this part we decide to clean the following aspects:
- Parameters: We will know how is structured the parameter's data and reduce the data.
- Countries: We will know the countries that are available and the model.
- Measurements:
- Locations:
