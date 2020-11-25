# MyBudget

## Deployed
* [Deployed App](https://offline-budget-tracking.herokuapp.com/)
* [Repository](https://github.com/celineross/My-Budget)

## Author
<p>Celine Ross</p>

## Description
<p>This app allows a user to store budget data online or offline in a browser, and output that data into a table and a graph for optimal viewing.</p>

<p>Here you can see the Add/Subtract Funds functionality.</p>
<img src="./screenshots/add.gif" alt="Add Funds Test" style="width:25%; height:25%">
<img src="./screenshots/subtract.gif" alt="Subtract Funds Test" style="width:25%; height:25%">

<br>
<br>

<p>When the network is offline, you can see in the console that the data entered is still logged locally.</p>
<img src="./screenshots/indexedDB.png" alt="Data is stored in the indexedDB while network is offline" style="width:50%; height:50%">

<br>
<br>

<p>When the network goes back online, the offline data store is fetched by the remote database and added to the rest of the data.</p>
<img src="./screenshots/fetch.png" alt="Fetching data from offline store" style="width:50%; height:50%">

## Requirements
<p>Express, Mongoose, MongoDB, Morgan, Compression, Node.</p>

## Installation
<p>After setting up dependencies, perform an npm install. Enter npm install [package name] for additional packages.</p>

## Usage
<p>App is deployed onto heroku, click link above to access.</p>

## License
<p>ISC</p>

## Contribution
<p>Please contact me if you'd like to contribute to this project.</p>