## Node Connect App
NodeJS Heroku Connect Sample

- Simple bootstrap node expressJS app.
- Establishes connection to Heroku Postgres.
- Queries a salesforce Heroku Connect Jobs Table.

Starting point for Salesforce/Heroku POC Demonstrations

#### Setting up your App

##### Heroku Connect fields
     From Heroku Connect Dashboard, add a Mapping for Account with the following fields:
     - account.name  
     - account.accountnumber
     - account.billingcity
     - accont.createddate


#### Changing the Database Query
- Update Postgres query in [index.js](https://github.com/joeyjmorales/node-connect/blob/master/index.js)
- Update HTML temnplate in [index.ejs](https://github.com/joeyjmorales/node-connect/blob/master/app/views/index.ejs)
