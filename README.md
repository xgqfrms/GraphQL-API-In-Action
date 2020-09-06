# GraphQL API In Action

> GraphQL API

```sh
$ yarn add express express-graphql graphql
# OR 
$ npm i -S express express-graphql graphql

```

https://www.cnblogs.com/xgqfrms/p/13620147.html


## PM2

```sh
$ yarn global add  pm2
# OR
$ npm install pm2 -g

# global
$ pm2 start server/index.js
```

```sh
$ yarn add -D pm2
# OR
$ npm i -D pm2

# local
$ ./node_modules/pm2/bin/pm2 start server/index.js

$ ./node_modules/pm2/bin/pm2 list

# $ ./node_modules/pm2/bin/pm2 stop ID
$ ./node_modules/pm2/bin/pm2 stop 0

$ ./node_modules/pm2/bin/pm2 monit
```


## nodemon

https://nodemon.io/

```sh
$ yarn global add  nodemon
# OR
$ npm i -g nodemon

# global
$ nodemon server/index.js
```

```sh
$ yarn add -D nodemon
# OR
$ npm i -D nodemon

# local
$ ./node_modules/nodemon/bin/nodemon.js server/index.js
```

https://www.cnblogs.com/xgqfrms/p/13621076.html


## jest


```sh
# jest
$ yarn add -D jest

# babel
$ yarn add -D babel-jest @babel/core @babel/preset-env babel-plugin-dynamic-import-node

```
