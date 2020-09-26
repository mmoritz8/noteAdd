 skeleton of a back-end for a note-taking application — think Google Keep. You want to be able to do all four CRUD actions on your notes: create, read, update, and delete.
You’re going to use Express as your framework, MongoDB as the database, and a package called body-parser to help deal with JSON requests.

You’re going to use the MongoClient to interact with your database. Note that you also initialize your app as an instance of Express, your framework.

MongoDB stores data in collections- which are exactly how they sound. In your case, you want to store your notes in a collection called — you guessed it — notes.

Say you wanted to get back the note you just created, by navigating to localhost:8000/notes/{the id}. In this case, that would be localhost:8000/notes/{id}.
