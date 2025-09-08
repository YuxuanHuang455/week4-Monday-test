# Share who report lifetime anxiety or depression - Data package

This data package contains the data that powers the chart ["Share who report lifetime anxiety or depression"](https://ourworldindata.org/grapher/share-who-report-lifetime-anxiety-or-depression?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on September 08, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Share - Question: mh7a - Have been anxious/depressed - Answer: Yes - Gender: all - Age group: all
Share of the respondents in the demographic group (country, age and gender) that marked a particular answer to the question.

To see the complete list of questions, visit https://cms.wellcome.org/sites/default/files/2021-11/WGM_Full_Questionnaire.pdf.

The share is obtained weighting the answers based on the characteristics of the participant. Data weighting is used to minimise bias in survey estimates and is intended to be used to generate nationally representative estimates within a country. The weighting procedure was fotrmulated based on the sample design and performed in multiple stages.

To learn more about this, you can read section "Data weighting" at https://cms.wellcome.org/sites/default/files/2021-10/wgm2020-methodology.pdf
Last updated: April 19, 2023  
Date range: 2020–2020  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Wellcome Global Monitor (2021) – processed by Our World in Data

#### Full citation
Wellcome Global Monitor (2021) – processed by Our World in Data. “Share - Question: mh7a - Have been anxious/depressed - Answer: Yes - Gender: all - Age group: all” [dataset]. Wellcome Global Monitor (2021) [original data].
Source: Wellcome Global Monitor (2021) – processed by Our World In Data

### Additional information about this data
Wellcome conducted the first Global Monitor – the largest-ever study of public attitudes to science and health – in 2018. The first wave covered topics such as whether people trust science, scientists and information about health, and attitudes towards the safety and efficacy of vaccines – a focus which has since proved incredibly forward-thinking.

In 2020, the Global Monitor's central focus was science's role in mental health.

The datasets and crosstabs cover the mental health sections of the WGM Survey 2020 conducted in 113 countries and territories worldwide on mental health views and experiences. The rest of the survey data will be published in subsequent data releases.


Relevant links:

• You can find the Wellcome Global Monitor 2020 full report at https://cms.wellcome.org/sites/default/files/2021-10/wellcome-global-monitor-mental-health.pdf
• Details on the methodology: https://cms.wellcome.org/sites/default/files/2021-10/wgm2020-methodology.pdf
• Details about the questionnaire: https://cms.wellcome.org/sites/default/files/2021-10/wgm2020-questionnaire.pdf
• Full questionnaire: https://cms.wellcome.org/sites/default/files/2021-11/WGM_Full_Questionnaire.pdf


Note 1: Data for answers where the demographic group had less than 100 participants are filtered out.

Note 2: Empty answers have been filtered out. Empty answers may appear because the question was not applicable to the respondent or the respondent did not answer the question.


    