

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


