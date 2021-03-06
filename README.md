# City Explorer API

**Author**: Nicholas Ryan
**Version**: 1.0.0

## Overview
This application was developed to help users navigate around a city and learn facts about it such as the weather forecast and any nearby hikes, while showing a map of the area. The user enters in a city or area they'd like to view and will be redirected to a page containing all the previously stated information available for the city/area. It works best for]cities within the US, but can generally find some data for any other areas as well.

## Getting Started
- Run NPM install from the root of this directory
- Get keys for the required APIs:
  - [Locationiq](https://locationiq.com/docs#forward-geocoding)
  - [Weatherbit.io API](https://www.weatherbit.io/)
  - REI Trails API
  - The Movie Database
  - 
- Example env file:
  - PORT=3000
  - GEOCODE_API_KEY=89324218957hafdshjqbf
  - WEATHER_API_KEY=18295712jfsahbgrew2342
  - TRAILS_API_KEY=12376432hfarewfh123321
  - MOVIE_API_KEY=dj21343215j1kg23313143
  - YELP_API_KEY=n8-213421543232143412434321-4321543252g1434215421ed-32143214
  - DATABASE_URL=postgres://USER:PASSWORD@DOMAIN:PORT/DBNAME

## Architecture
The back end for this app utilizes JavaScript as the programming language, as well as packages such as express (for creating the server), cors (provides the Connect/Express middleware), dotenv (for reading the file), nodemon (to run a local server), Postgres (for SQL database), and superagent (collects data from APIs).

## Change Log
05-12-2020 4pm - Application now utilizes APIs to collect data to render rather than using .json files.

05-13-2020 4pm - Application now uses an SQL database to store and reload the location API data for faster rendering.

## Credits and Collaborations
Special thanks to:
- Nicholas Carignan
- Chance Harmon


## Features
### 5/11/2020
Number and name of feature: #1 Repository Set Up

Estimate of time needed to complete: 15 min.

Start time: 3:30 p.m.

Finish time: 3:50 p.m.

Actual time needed to complete: 20 min


Number and name of feature: #2 Locations

Estimate of time needed to complete: 1 hour

Start time: 4:00 p.m.

Finish time: 5:15 p.m.

Actual time needed to complete: 75 min


Number and name of feature: #3 Weather

Estimate of time needed to complete: ~ 75 min

Start time: 5:20 p.m.

Finish time: ~7 p.m. w/ 30 min break

Actual time needed to complete: ~70-75 min


Number and name of feature: #4 Errors

Estimate of time needed to complete: 5 min

Start time: 12:45 p.m. (5/12/20)

Finish time: 12:50 p.m.

Actual time needed to complete: 5 min.


### 5/12/2020
Number and name of feature: #1 Data Formatting

Estimate of time needed to complete: 20 min.

Start time: 12:50 p.m.

Finish time: 1:10 p.m.

Actual time needed to complete: 20 min


Number and name of feature: #2 Locations

Estimate of time needed to complete: 30 min.

Start time: 1:10 p.m.

Finish time: 1:30 p.m.

Actual time needed to complete: 20 min


Number and name of feature: #3 Weather

Estimate of time needed to complete: 30 min.

Start time: 2:10 p.m.

Finish time: 2:30 p.m.

Actual time needed to complete: 20 min


Number and name of feature: #4 Trails

Estimate of time needed to complete: 30 min.

Start time: 2:40 p.m.

Finish time: 3:15 p.m.

Actual time needed to complete: 35 min

### 5/13/2020
Number and name of feature: #1 Database

Estimate of time needed to complete: 15 min.

Start time: 1:30 p.m.

Finish time: 1:50 p.m.

Actual time needed to complete: 20 min


Number and name of feature: #2 Server

Estimate of time needed to complete: 25 min

Start time: 1:50 p.m.

Finish time: 3:10 p.m. (~45 min break for code challenge)

Actual time needed to complete: 35-40 min


Number and name of feature: #3 Deploy

Estimate of time needed to complete: 10 min

Start time: 3:15 p.m.

Finish time: 3:30 p.m.

Actual time needed to complete: 15 min.


Number and name of feature: #4 Server

Estimate of time needed to complete: 45 min - 1 hr.

Start time: 3:45 p.m.

Finish time: INCOMPLETE

Actual time needed to complete: ________ min.

### 5/14/2020
Number and name of feature: #1 Movies

Estimate of time needed to complete: 45 min.

Start time: ~3:15 p.m.

Finish time: ~4:30 p.m.

Actual time needed to complete: ~75 min


Number and name of feature: #2 Yelp

Estimate of time needed to complete: 30 min.

Start time: 4:40 p.m.

Finish time: 5:15 p.m.

Actual time needed to complete: 20 min


Number and name of feature: #3 Modularize

Estimate of time needed to complete: 30 min.

Start time: 5:15 p.m.

Finish time: 5:35 p.m.

Actual time needed to complete: 20 min
