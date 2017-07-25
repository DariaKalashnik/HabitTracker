# Habit Tracker [HabitTracker]

##### 9th Project for [Android Basics Nanodegree by Google](https://www.udacity.com/course/android-basics-nanodegree-by-google--nd803)

### App description:
1. Project has contains no UI.
2. There exists a contract class that defines name of table and constants.
Inside the contract class, there is an inner class for each table created.
3. There is a single insert method that adds values of two different datatypes (INTEGER, STRING)
into the database using a ContentValues object and the insert() method.
4. There is a single read method that returns a Cursor object. It should get the data repository in read and use the query()
method to retrieve at least one column of data.
5. All data insertion and reading are done using direct method calls to the SQLite database in the SQLiteOpenHelper class.
