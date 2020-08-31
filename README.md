
# Rocket Launches Code Simulation

### Goal
Create an API for a rocket launch application that will give its users information about the history of rocket launches since 1959.

### Requirements
Your API should return the following data about rocket launches for a given rocket __company__ and/or __date range__.  The API will return:

* Average launch cost (excluding nulls)
* Percent of launches where `mission_status` is `success`
* The most popular month for rocket launches
* Top three `launch_locations`
* Top three __countries__ where `launch_locations` take place

Your API can be written in any language/framework and use any transport protocol supported by a modern web browser. Please include a simple API reference (i.e. a curl example) so a client application developer can use it. API authentication is not required and assume your API is public. The simulation should take less than three hours to complete.

##### There are four tables of data:

1. rocket_launches ([csv](https://github.com/sourcetable/rocket-launch-api-simulation/blob/master/csv/rocket_launches.csv))
2. rocket_companies ([csv](https://github.com/sourcetable/rocket-launch-api-simulation/blob/master/csv/rocket_companies.csv))
3. mission_status ([csv](https://github.com/sourcetable/rocket-launch-api-simulation/blob/master/csv/mission_status.csv))
4. launch_location ([csv](https://github.com/sourcetable/rocket-launch-api-simulation/csv/blob/master/csv/launch_location.csv))


### Connect to the database
The data is stored in Postgres database for convenience. It is open to all IP addresses.  If you have connection difficulties please contact us immediately.  You can use the provided database or uplaod the csv files (see csv above) to a data store of your choice.

| PostgreSQL Database| |
|---|---|
| Server|*****|
| Port | 5432 |
| User | **** |
| Password | ****	 |
|database| **** |

* A .env file will be included in the instructions

### Communication
We will invite you to a public slack channel to directly communicate with us while you complete the simulation. Feel free to ask any questions.

### What we are looking for:

* Clearly thought out application structure
* Logically chosen variable and function names
* Git [best practices](https://guides.github.com/introduction/flow/)
* A readme.md with clear instructions on how to run the API


### How to submit your solution
* Make a private fork or clone of this repo
* When your done invite [@jeffj](https://github.com/jeffj) as a [admin](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) to your repo and send __jeff@sourcetable.com__ an email.
