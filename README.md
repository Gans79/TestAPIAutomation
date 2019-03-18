Author : Ganesh Ranganathan
Role : Senior Automation Engineer 
Automation Tool : Newman 

Setup steps: 

Install NodeJS : https://nodejs.org/en/download/
Intall newman   : npm install -g newman

Run Steps in CLI :
Download Collection file from repo: Weatherbit.postman_collection.json
Download data file from repo : Data-Scenarioall.csv
Open commnad line: cmd, setpath to downloaded files
Run as Newman test : newman run Weatherbit.postman_collection.json -d Weatherbit-data.csv
Run as Node js package (recommended) : node TestWeatherbit.js

