#Rocket Launches Code Simulation
-
###Assignment
Create an API for a rocket launch application that will give a use information about the history of rocket launches since 1959. 

###Requirements
Your API should return the following data about rocket launches for a given __company__ and/or ___date range___.  The API will return:

* Average launch cost (excluding nulls)
* Percent of launches where `mission_status` is `success`
* Most popular month for rocket launches
* Top three `launch_locations`
* Top three launch __countries__ for the `launch_locations`

Your API can be written in any language/framework and can use any transport protocol a modern web browser can communicate with. The API should be extensible to suit the inevitable design changes we expect on the frontend.  The solution should take less than three hours to complete. 


#####There are three tables of data:

1. rocket_launches
2. rocket_companies
3. mission_status
4. launch_location


###Connect to the Database
The data connection is below. It is open to all IPs.  If you have connection difficulties please contact us immediately.

| Postgres Database| |
|---|---|
| Server|lallah.db.elephantsql.com|
| Port | 5432 |
| User | tyqnhaaq |
| Password | 	M4SbR7Kk2L-dVGEmXXfSrvNnaZAdBoys |
|database| tyqnhaaq |


###What we like:

* Clearly thought out application structure
* Logically chosen variable and function names
* A git history that can followed
* A readme.md that can be be used to get a _development_ environment of API running


###How to submit your solution
* Make a private fork or clone of this repo
* When your done invite [@jeffj](https://github.com/jeffj) as a [admin](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) to your repo and send __jeff@sourcetable.com__ an email.
