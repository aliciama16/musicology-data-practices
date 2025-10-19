# Data Dictionary

A data dictionary is important because ____. 

Find some examples here:
* Test Example

_Last Updated: 2025-10-19_

------------
Data Dictionary
------------

This data dictionary is for my Musicology dataset [link here].

Here is how to learn more about formatting tables in Github: https://stackoverflow.com/questions/39378020/how-to-display-table-in-readme-md-file-in-github
github resources: https://www.markdownguide.org/basic-syntax/

| Column | Data Type | Description | Allowed / Example Values |
|--------|-----------|:------------|--------------------------|
| DOI/URL | URL | DOI or URL link to an academic article | https://doi.org/10.1525/jams.2021.74.1.43 |
| Title | string | Academic Article Title Name | Beethoven’s Theologian |
| Author | string | First and Last Name of the Author | Nicholas Chong |
| Journal Name | string | Name of the Journal the academic article was published in | Journal of the American Musicological Society |
| Publication Year | date (YYYY) | Year the academic article was published | 2021 |
| Primary Sources | string (list)| A list of primary sources mentioned in the article seperated by ; | personal letters; musical scores; concert programs |
| Secondary Sources | string (list)| A list of secondary sources mentioned in the article seperated by ; | scholarship; newspaper articles |
| Primary Format | string (list)| A list of primary formats of data mentioned in the article seperated by ; | audio; image scans; text documents |
| How Accessed? | string (list)| A list of the ways in which the data was accessed (e.g. was it accessed via an archive? A museum? A library?) | personal archive; digital library |
| Time Period | string | The time period the academic article focuses on. Metadata standard to be determined later | Romantic
| Subfield | string (list)| A list of the academic subfields under musicology that this articles falls under. Metadata standard to be determined later | historical musicology; music theory |
| Data Deposited? | enum | Was any data from the academic study deposited anywhere? Only allow Federer, et. al 2018 categories | No statement/ Not shared | 
| DOI/URL of Data Deposit | URL | DOI or URL link to where data outcomes from the academic study were deposited (if any) | https://doi.org/10.1525/jams.2021.74.1.43 |
| What data respository? | string | The name of the data despository where data was deposited (if any) | Dataverse |
| DOI of Cited Data Paper? | URL | The DOI link if the academic article used a data paper within their research | https://doi.org/10.1525/jams.2021.74.1.43 |
| Funding Sources | string | The name of the funding source for the article | None explicitly mentioned OR Indiana University Center of Philanthropy and the Rockefeller Archive Center |
