# MongoDB $inc operator error: string value instead of number

This example demonstrates an error that occurs when using MongoDB's $inc operator with a string value instead of a numerical value.
The `$inc` operator is used to increment a numerical field in a document.  In this case, we incorrectly pass a string "10" to the likes field.