Creat a MySQL db with the following details:

    user: 'project',
    password: 'project',
    database: 'project'

Run 1st time to add a table users and a 2nd time to add a user:

    node setup.js

Run to get a JWT token:

    node create-token.js

Create the tables (employee, department) in MySQL db:

    TODO (check file data.json)

Run server (pass the JWT token when calling the API with auth methods):

    node app.js
