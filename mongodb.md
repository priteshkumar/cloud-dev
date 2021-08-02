## MongoDb notes

> It uses BSON (binary representation of JSON to store records in form of documents)

> All single document writes are atomic


### Query with logical operators

 `db.collection.find({$and: [{condition 1},{condition 2}...]})`

 `db.collection.find({$or: [{condition 1},{condition 2}...]})`

 `db.collection.find({field: {$not: {condition}}})`
