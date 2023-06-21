# strawberryDB
A simple database format built with Python.

### What is strawberryDB?
StrawberryDB is a database format based on columns (up/down) and entries (left/right).

A database file (.sdb) is what contains these columns and entries.

A database file would look something like this:
```
customers
username|id|moneySpent|currentGiftCardCredit
admin|1|12421.31|9999.99
coolio|2|37.21|0
...
```

The `customers` line is the name of our sample database.

The `username|id|moneySpent|currentGiftCardCredit` are the names of all the columns *(separated by |)*.

The rest of the lines are entries, which are the actual data in the database. They relate to the columns, like a spreadsheet.

