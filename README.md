# Bakman Water Project


## Installing the project

```sh 
git clone https://github.com/Shift3/bakman-water-new.git
```


### /client

```sh
npm install
```

```sh
bower install
```

```sh
gulp serve
```

### /server

```sh
npm install
```

```sh
env $(cat .env) nodemon index.js
```



## Project Structure

### /client
```
/src - All client side code

/src/app - App components and partials
/src/app/[component] - one component of the project (usually with a controller, partial, and scss)
/src/app/components - smaller components with multiple dependents
/src/app/components/[component] - small component (usually services and directives)
/src/app/index.config.js - main config function
/src/app/index.module.js - import all javascript components here
/src/app/index.route.js - defines all states for ui router
/src/app/index.run.js - main run function
/src/app/index.scss - main scss file

/src/assets - Static assets

/src/index.html - Main index file (dependencies injected here)
```

### /server

```
/controllers - all controllers for routes separated by model
/controllers/index.js - exports all controllers

/models - all mongoose models
/models/index.js - exports all mongoose models
/models/sequelize - all sequelize models
/models/sequelize/index.js - exports all sequelize models

/config.js - temporary config file

/helper.js - all helper functions

/middleware.js - all router middleware functions

/routes.js - all app endpoints using exported controllers and middleware

/server.js - main server file

```

<!--Directory | Information -->
<!----- | --- -->
<!--sup | hi-->
<!--1 | 2 -->
