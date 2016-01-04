**ABOUT**

*toDoList* is a simple application built on the *MEAN* stack for managing tasks.

**SETUP**

1. ```git clone https://github.com/SKEPT1K/toDoList.git```
2. Configure the mongo connection via the *MongoClient* string:

`mongodb.MongoClient.connect('mongodb://127.0.0.1:27017/test', function (err, database){`

    `...`

3. Set the *collection* and *port* to be used:

    `itemsCollection = db.collection('items');`

    `app.listen(3000);`

4. Create the database/collection.
5. Run `node app.js`

**LICENSE**

MIT
