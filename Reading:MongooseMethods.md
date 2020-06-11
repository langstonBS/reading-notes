## instance method
- findSimilarTypes 
- it allows to have a method on the schema kinda like a class that alows us to acsess the data
- dont use arro funtions

## Statics
- static funtions on scemas 

## middle whare (pre and post hooks)

- Mongoose has 4 types of middleware: document middleware, model middleware, aggregate middleware, and query middleware

###  document middleware
- Document middleware is supported for the following document functions. In document middleware functions, this refers to the document.
- validate
- save
- remove
- updateOne
- deleteOne
- init (note: init hooks are synchronous)

### model middleware

### Query middleware
- Query middleware is supported for the following Model and Query functions. In query middleware functions, this refers to the query.
- count
- deleteMany
- deleteOne
- find
- findOne
- findOneAndDelete
- findOneAndRemove
- findOneAndUpdate
- remove
- update
- updateOne
- updateMany

### Aggregate middleware
-  Aggregate middleware executes when you call exec() on an aggregate object
- aggregate

### Model middleware
- insertMany

