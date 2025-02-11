# MongoDB $inc operator error with string field
This repository demonstrates an error that occurs when using the `$inc` operator in MongoDB to increment a field that is not a number.  The incorrect code attempts to increment a string field, which results in an error.
The solution showcases the proper usage of the `$inc` operator, ensuring the target field is a number. 
## Setup
1.  Install MongoDB.
2.  Run MongoDB.
3. Create a collection named 'myCollection' and insert a document with a numeric field to test the code.