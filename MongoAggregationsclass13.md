## Mongo Aggregations

### Aggregation Pipeline
- The aggregation pipeline is a framework for data aggregation 
- $match maches documentation 
- $group groupes together
- takes in an array of data

#### Pipeline
- The MongoDB aggregation pipeline consists of stages.
- maching piplines and getting more data

#### Pipeline Expressions
- can do mathamaictcall application
- grouping documents will help with mathimatical operations

#### Aggregation Pipeline Behavior
- In MongoDB, the aggregate command operates on a single collection, logically passing the entire collection into the aggregation pipeline.

#### Pipeline Operators and Indexes
- MongoDB’s query planner analyzes an aggregation pipeline to determine whether indexes can be used to improve pipeline performance
- $match: The $match stage can use an index to filter documents if it occurs at the beginning of a pipeline.
- $sort: The $sort stage can use an index as long as it is not preceded by a $project, $unwind, or $group stage.
- $group: The $group stage can sometimes use an index to find the first document in each group if all of the following criteria are met
- 