I have written an npm module for [Clockify](https://clockify.me) REST APIs.

[NPM Package](https://www.npmjs.com/package/clockify-npm).

[Git Hub](https://github.com/sinumohan/clockify-npm).

For API docs Please refer [developers-api](https://clockify.me/developers-api). 


### Installation
``` npm install clockify-npm ```

### Examples
```
const Clockify = require('clockify-npm');

Clockify.SetKey('YOUR_API_KEY');

// Get all Workspaces of the current User
Clockify.Workspaces.get()
    .then((data) => {
        console.log(data)
    }).catch((err) => {
        console.error(err);
    })

// Create a new Workspace
Clockify.Workspaces.add('My Work Space')
    .then((data) => {
        console.log(data)
    }).catch((err) => {
        console.error(err);
    })
```
