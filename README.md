# Advertisement Campaign Management System

## Web app
- Create an angular app to add and maintain Campaigns for an advertisement agency. 
- Please, collect, store and retrieve the following details to manage campaigns. Campaign Name  - free text
  -	Short Description – free text
  -	Start Date - date
  -	End Date – date 
  -	Advertisement content. ( content displayed in the stall )  - free text
PS: Please, try to use the concepts that we have discussed during our sessions.

## Node app
Create a node JS app that serves data from database.

For creating node app. Please find the below instructions. 
- Create new folder, 
- Create a js filer under the folder

```
var express = require('express');
var cors = require('cors');

var app = express();

app.use(cors());

app.get('/api/employees',(req, res) => {
    res.send([{"Id": 1, "Firstname": "Balaji", "Lastname": "Ravichandran"},
    {"Id": 2, "Firstname": "Bala", "Lastname": "Ra"}]);
});

app.listen(5000);

console.log("server hosted at port number 5000");

```
Install the following packages.
```
npm install express
npm install cors
```
Start node app
```
node filename.js
```
the above API can be consumed with the below URL
``` http://localhost:5000/api/campaigns ```

## Database
Please, create table(s) that are required to store the collected information. 
You’re free to use any database of your choice.

## Useful commands

install angular cli
` npm install -g @angular/cli `

check angular cli version
` ng --version `

create new angular project
` ng new angular-projectname `

create new component
` ng generate component component-name `

create new service 
`ng generate service service-name `

restore packages 
`npm install`

start angular app
` ng serve --open `

start node app 
` node javascript-filename.js `



