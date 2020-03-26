# South Africa Cases for the covid-19 disease

**The NICD has stopped updating detailed data for the cases**.\
The University of WITS also has a visualization site that links to NICD data,
[COVID-19 South Africa Dashboard](https://datastudio.google.com/u/0/reporting/15817068-62f2-4101-8e0f-385e2ddd9326/page/1M).

Data taken from the [NICD](http://www.nicd.ac.za/) website.

## Data Format
The format of the data is presented in a .csv file and it follows the format of the NICD data entries on the
NICD website. 

Example:
|Date|Province|Age|Sex|Country|
|---|---|---|---|---|
|12-Mar-2020 06:37|KwazuluNatal|38|male|Turkey|

where **Country** is the suspected place of where the person might have been infected. For South Africa this
would be defined as **local**. The **Date** column is the date on which the NICD uploaded the data to their website.


## NICD Data issues
There are a number of data entry errors/omissions on certain days from the NICD website.

1. Missing the first 14 official cases that was not listed on the [NICD](http://www.nicd.ac.za/).

2. [20 March 2020](http://www.nicd.ac.za/covid-19-update-22/)
   * Western Cape Province  
   * A 34-year-old who travelled to the Netherlands ( Missing the sex of the person )
   * A 26-year-old who travelled to the Netherlands ( Missing the sex of the person )
   * A 29-year-old with pending travel history (Missing the sex of the person )
   * A 58-year-old who travelled to the United Kingdom, Austria and Tanzani (Missing the sex of the person)
   * A 62-year-old who travelled to the United Kingdom, Austria and Switzerland (Missing the sex of the person)
  
# Other Source
[Covid Data Resources](https://www.codevscovid19.org/) 
