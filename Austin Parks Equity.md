# Austin Parks Equity

**(8-Jul)**

Park Score, static, our tool would be more dynamics.

Collin at Parks Foundation, db of park advocates. funding

Participatory Budget, where do you want to see the money go, given this tool?

Short-Term Goal:

Baseline Park Need Score

*   Park Access Score

current deficiency map fails because parks land does not equate to value (number of amenities)

Build towards demonstration for Parks Foundation

*   get their input on how to tweek scoring, presentation, etc.

Old Report from Parks Equity Working Group

[](https://keepaustinwonky.files.wordpress.com/2015/07/urban-parks-workgroup-final-report.pdf)https://keepaustinwonky.files.wordpress.com/2015/07/urban-parks-workgroup-final-report.pdf

**(26-June)**

Hey y'all have a feature request forum / list? Fine I'll just post here :)

I'm [Alex Schmitz](/ep/profile/skygNL2xSYL), I met [Katie Yoder](/ep/profile/DyM2HLFPRvn) at Greg Casar's D4 parks meeting. I love this tool - I wish I had had something like two years ago, we had do all this from scratch for our presentations, and it didn't look this good. I wish I knew JS or more about GIS so I could add features to this tool, but getting gulp running on Win is about my limit. 

As much as this tool rocks, I'd love for the ranking information to be dynamic. What if someone built a "what if" simulator - ie.: what if D4 built a new 13 acre park, how would this affect our park equity rankings? What if we ignored all pocket parks, all ISD parks, how would _that _affect rankings, etc?

Also, I see the notes below talking about getting away from districts (or just make districts one possible layer, with the following a diff layer, etc). Would it be possible to:

*   implement the heat map idea outlined below
*   add the district boundaries back on top of the heatmap, and calculate average "heat" of each district. 

Just my thoughts. Thanks for doing this! 

**(22-May)**

John talked to folks in PARD and they are on board.

*   Ricardo Soliz - Division Mgr at Park Inequity
*   Sarah Hensly - Development Director 

John will e-introduce us and follow up with City Demographer.

<u>June 3rd - Community Meeting</u>

*   Focus on presenting the status of District 4

        *   rank vs other districts.

*   Some demographic info would help

Long term, focus less on the districts

*   Heatmap is better than District Maps. Idea is to create district allies.

<u>Next Steps</u>

![](https://hackpad-attachments.s3.amazonaws.com/openaustin.hackpad.com_H1aHh4ggGaQ_p.378003_1432811580973_undefined)

*
*   [](http://www.capcog.org/data-maps-and-reports/geospatial-data/)http://www.capcog.org/data-maps-and-reports/geospatial-data/ 

*   Decided between

        *   heatmap powered by park centroids.
    *   pick a census boundary (tracts, probably) and color in each tract based on amount of park acreage.

*   Or do both.

**(12-May)**

<u>Questions for **John</u>**<u>:</u>

*   district demographic data ([link](http://www.austintexas.gov/page/demographic-data))

        *   renters vs. owners by district: [](http://www.austintexas.gov/sites/default/files/files/Planning/Demographics/Tenure_by_Income_bracket_CoA_2013.pdf)http://www.austintexas.gov/sites/default/files/files/Planning/Demographics/Tenure_by_Income_bracket_CoA_2013.pdf

*   park maintenance costs
*   schedule a meeting for next week, after Monday. Before community meeting on Park on Tuesday, May 26
*   Stated Goal in Greg's email: 

        *   Previous city councils established a goal in which all residents living in the urban core should live within 1/4 quarter mile walking distance of a publicly accessible and child-friendly park.
    *   How many ppl in each district currently live within a 1/4 mile of a park?

                *   How is the urban core defined?
        *   How do we define publicly accessible and child-friendly?

        *   Impact News Story:

                *   [](http://impactnews.com/austin-metro/northwest-austin/north-austin-green-space-becomes-a-priority-for-council/)[http://impactnews.com/austin-metro/northwest-austin/north-austin-green-space-becomes-a-priority-for-council/](http://impactnews.com/austin-metro/northwest-austin/north-austin-green-space-becomes-a-priority-for-council/)

*   [Katie](/ep/profile/DyM2HLFPRvn) 

*   Making screenshots of examples of parks on the border or surrounded by a district. 

        *   How to account for those?

*   Going to consider including park acreage data directly into districts shapefile properties and export a clean GeoJSON from ArcMap
*   [](http://ogre.adc4gis.com/)http://ogre.adc4gis.com/

*   setup Github and send [Mateo](/ep/profile/yThAdj5FweD) with username
*   [Mateo](/ep/profile/yThAdj5FweD)

*   fork exisiting repo from my github account to Open Austin

*   add kyoder as collaborator (need Chip to fix github permissions)

*   replace park shapefile with updated data

*   update acreage data with [updated data](https://docs.google.com/spreadsheets/d/1ZXHZxrVlplLKgpObbTxZB26uHuX3ZaYK6GJTeQddhXY/edit#gid=0)

*   update park colors to vary by type

*   merge [Katie's methodology](https://docs.google.com/document/d/1A_VyJhxf8yajN_icSXOI9zebVLDYp5mDTs12SGLVUy8/edit) into existing README

*   elaborate README section on local setup

*   add capmetro transit stops

I wish we had the shapefile for this neighborhood breakdown:

[](http://www.austintexas.gov/sites/default/files/files/Planning/Demographics/Neighborhood_Reporting_Areas.pdf)http://www.austintexas.gov/sites/default/files/files/Planning/Demographics/Neighborhood_Reporting_Areas.pdf

**(29-April)**

<u>Next Steps</u>
<ul class="taskdone"><li>In right aside, think about what data to display

*   Pop under 18
*   Demographic value(s) for Income
*   Housing Data
*   Total Park Acres

*   Total Park Maintenance 

*   Count of Parks by Type
</ul class="taskdone">

*   compare John's excel data to existing GIS shapefile. [klyoder94@gmail.com](https://openaustin.hackpad.com/ep/profile/DyM2HLFPRvn)
*   calculate Park Acreage by District & ZIP with **ArcMap** [Katie Yoder](https://openaustin.hackpad.com/ep/profile/DyM2HLFPRvn)

*   Add Zip Layer to Leaflet [Mateo Clarke](https://openaustin.hackpad.com/ep/profile/yThAdj5FweD)

*   Request Updated GIS Data from Sara Smith [Mateo Clarke](/ep/profile/yThAdj5FweD)
*   Talk to Miles about Crime Data API. [Mateo Clarke](https://openaustin.hackpad.com/ep/profile/yThAdj5FweD)
*   Reach out to GIS devs [klyoder94@gmail.com](https://openaustin.hackpad.com/ep/profile/DyM2HLFPRvn)
*   Screen shots of other map-centric apps with good design and data presentation. [klyoder94@gmail.com](https://openaustin.hackpad.com/ep/profile/DyM2HLFPRvn)

This [Park Data](https://data.austintexas.gov/dataset/City-Of-Austin-Parks/99qw-4ixs) looks like it updates more frequently than [our original source](ftp://ftp.ci.austin.tx.us/GIS-Data/Regional/coa_gis.html).

Here is the [GIS map](http://austintexas.gov/GIS/ParksWeb/) that is already available. Gives us a clue of what layers are available.

When it comes to cost there are a couple of potential sources: Annual Maintenance vs. Bond projects

<u>Contacts in PARD:</u>

*   Allison Hardy, GIS Data Manager at PARD
*   Anthony Cardenas, Maintenance Cost, Program Manager for MicroMain
*   Randy Scott, Park Deficient, Park Land Dedication

**(24-April)**

<u>Summary</u>

Mateo & Katie met with John Lawler (Policy Director for Greg Casar) to get oriented on the context and scope for this project. The goal is to create map-centric app that can provide data about parks distribution and demographic data by city council districts, ZIP Codes, etc.

<u>App Features/Ideas/Specs</u>

Live Demo (very rough): [](http://mateoclarke.github.io/Austin_Parks_Acreage/)http://mateoclarke.github.io/Austin_Parks_Acreage/

Github Repo with data folder: [](https://github.com/mateoclarke/Austin_Parks_Acreage)https://github.com/mateoclarke/Austin_Parks_Acreage

<u>Data Needs/Wishlist</u>

*   More information about specific parks

        *   date established
    *   average annual maintenance costs by park or park type

*   Transit stops: [](https://www.capmetro.org/datastats.aspx?id=129)https://www.capmetro.org/datastats.aspx?id=129
*   City Demographer may have info about informal data not captured by census.
*   elementary schools close to parks

        *   soccer fields vs playgrounds, other facilities

*   Public Health data: [](http://www.cdc.gov/nchs/data_access/ftp_data.htm)http://www.cdc.gov/nchs/data_access/ftp_data.htm
*   Housing

        *   apartment dwellers vs property owners, etc

*   Socioeconomic class
*   Population under 18
*   access to fitness and healthy food
*   Crime data

<u>Links/Resources </u>

*   [Google Docs](https://docs.google.com/spreadsheets/d/1ljr1-aQHiDdhThPt_N-5Xj5leDON_RasS9l4ukHoDfI/edit?usp=sharing) with John's Excel Data Geocoded.
*   [Data Driven Detroit](http://datadrivendetroit.org/)