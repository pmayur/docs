# Popular Packages
Lists common and popular npm packages to make your work easier
## [Config](https://www.npmjs.com/package/config) 
this package helps us define config variables, by default it is supposed to be present in a directory named `config` at the project root, it needs to have configuration environment files like `development.json`, `production.json`, `test.json` etc, the directory can be configured to something else and more advanced features exist for multi instance deployments etc. For choosing what config file to look into it looks at the `NODE_ENV` variable and if its `undefined`, it defaults to the value `development`

 ## [Winston](https://www.npmjs.com/package/winston) 
this package helps us to log items to the console as well as gives configuration options to persist the logs in a file. It has a lot of configuration like for timestamps, type / level of logs eg: debug, error, info etc