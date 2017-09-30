# Here Comes The Story Of The Hurricane
## How to build 'The Hurricane Dashboard' in Tableau
### Robert M Chapple

As part of my company's Learn Day initiative, I'm giving a 'how to' tutorial on building a visualisation of the NOAA HURDAT2 datasource in Tableau. In other words, I'm demoing 'The Hurricane Dashboard'.

Why this particular dashboard? Well ... the building process showcases a nice range of beginner and intermediate techniques, but mostly it is relatively quick to make and delivers spectacular results! What's not to like?

## This repository includes:
### HurricanesData.csv
This csv file contains an edited version of the NOAA HURDAT2 dataset. It removes all data columns not necessary to create the dashboard, as well as reconfiguring the data so it can be read by Tableau. For instance, the Latitude and Longitude in the original is given as degrees E, W, & N and has been changed to decimals. Time and date have been changed from the original to break them out into individual data columns and in formats Tableau can read. In addition, I've added columns to provide storm-level identifiers and describe the order in which points should be drawn, both of which are required by Tableau to create this visualisation.

**I do not own this dataset**, and this edited version is supplied for the purposes of education only.

The original HURDAT2 dataset is available from NOAA here: <http://www.nhc.noaa.gov/data/>

### HurricanesDashboard.twbx
This Tableau Packaged Workbook contains the completed dashboard and worksheets. Feel free to download and explore!
(Or it will be, once I complete it! This is a 'work in progress' right now.)

The title comes from Bob Dylan's song Hurricane (co-written with Jacques Levy), from his 1976 album, Desire. But, of corse, you knew that.


