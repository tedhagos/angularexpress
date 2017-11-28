
# First thing to do

```
npm install
bower install
```
This will pull all libs in the dependencies of bower.json and package.json



# Populate the DB

Run the  mongo daemon
```
mongod
```

On another terminal, use the dbscript.js to populate the db
```
mongo localhost/authorsdb --quiet dbscripts.js
```

# Run the Express Server endpoints

```
nodemon server.js
```


