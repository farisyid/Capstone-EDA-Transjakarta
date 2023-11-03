# Capstone-Module-2-DataSet-TransJakarta
Hello everyone, I am excited to present my second capstone project as part of the Data Science Bootcamp at Purwadhika. This project represents the culmination of my learnings from Module 2, which focuses on Data Analysis. During Module 2, I acquired skills in Data Analysis using MySQL, Python for Data Analysis, Fundamental Statistics, and Data Visualization.
This project is end-to-end analyst of the dataset. In this project used Public TransJakarta dataset from [Dataset](https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction) with dummy data from master data.

You could see the Tableu Visualization [my Tableu](https://public.tableau.com/app/profile/faris.rasyid/viz/TransJakartaDataset/Story1)

You could see my presentation [EXPLORATORY DATA ANALYSIS.pptx](https://github.com/farisyid/Capstone-Module-2/files/13247744/EXPLORATORY.DATA.ANALYSIS.pptx)

### **Overview**
TransJakarta is the first Bus Rapid Transit (BRT) transport system in Southeast and South Asia with the longest track in the world (208 km). The BRT system was designed based on the TransMilenio system in Bogota, Colombia. As of 1 February 2004, TransJakarta was officially in operation. 

In 2011, TransJakarta implemented an integrated fleet management system. One of them is integrating with bus operators to provide Busway feeder services for its customers. In this year, TransJakarta also began preparations for the opening of corridor 11 & 12 services and replaced corridor 1 buses with articulated buses.

TransJakarta prepared for the opening of new corridors such as the preparation of operator tenders, construction of Busway lanes, ramps, bus stops and other supporting infrastructure. In 2013, TransJakarta also began implementing the e-ticketing system for all corridors as well as the integration of the e-ticketing system with Busway feeders and other public transport.

On 27 March 2014, TransJakarta changed its status to BUMD (Regional Owned Enterprise) and officially changed its name to PT Transportasi Jakarta. Plans to open new corridors continue, innovations were launched for the convenience of customers.

In April 2016, Transjakarta officially operated a special pink bus for women in commemoration of Kartini Day. This women-only bus can be found in corridor 1 (Blok M - Kota). Transjakarta will also add women-only buses in other corridors.

Transjakarta Site Visit: Senior Traveler was held for the first time. Participants for the first time were followed by 40 elderly people from Panti Werdha Sasana Bina Mulya. This activity runs regularly every week and is attended by participants aged 60-70 years from various social institutions. The hope is that in the future, Transjakarta will not only be comfortable and safe for customers in general but also become a public transport that is friendly and easy for small children and elderly customers.


### **Problem Statement**
In the company's consistency to **overcome traffic congestion**, the company will continue to **innovate by improving services at stops that need development**. Thus, the Transjakarta user community can comfortably use Transjakarta facilities and can increase its users in order to unravel congestion in Jakarta.

To answer these problems I will provide the following references:
1. Which corridor is the busiest corridor
2. Which corridor is visited by many women
3. Which corridors are visited by the elderly 4.

### **StakeHolder**
PT. Transjakarta Bussiness and Development Team.

This dataset contains age, gender, departure place, destination place, and kind of transportation PT. TransJakarta user. there was 22 column in dataset Transjakarta :
|No. | Column Name | Detail |
|----|------------|------------|
|1.	|transID| Unique transaction id for every transaction|
|2.	|payCardID| Customers main identifier. The card customers use as a ticket for entrance and exit.|
|3.	|payCardBank| Customers card bank issuer name|
|4.	|payCardName| Customers name that is embedded in the card.|
|5.	|payCardSex| Customers sex that is embedded in the card|
|6.	|payCardBirthDate| Customers birth year|
|7.	|corridorID| Corridor ID / Route ID as key for route grouping.|
|8.	|corridorName| Corridor Name / Route Name contains Start and Finish for each route.|
|9.	|direction| 0 for Go, 1 for Back. Direction of the route.|
|10.|tapInStops| Tap In (entrance) Stops ID for identifying stops name|
|11.|tapInStopsName| Tap In (entrance) Stops Name where customers tap in.|
|12.|tapInStopsLat| Latitude of Tap In Stops|
|13.|tapInStopsLon| Longitude of Tap In Stops|
|14.|stopStartSeq| Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.|
|15.|tapInTime| Time of tap in. Date and time|
|16.|tapOutStops| Tap Out (Exit) Stops ID for identifying stops name|
|17.|tapOutStopsName| Tap out (exit) Stops Name where customers tap out.|
|18.|tapOutStopsLat| Latitude of Tap Out Stops|
|19.|tapOutStopsLon| Longitude of Tap Out Stops|
|20.|stopEndSeq| Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.|
|21.|tapOutTime| Time of tap out. Date and time|
|22.|payAmount| The number of what customers pay. Some are free. Some not.|
