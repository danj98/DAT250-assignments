# Expass3 report

## Technical problems
No technical issues were encountered while installing mongodb on Arch Linux as 
there was a precompiled binary available on the Arch User Repository.

## Screenshots

### Validation
![val](https://github.com/danj98/dat250-assignments/blob/main/data/pgp-verified.png)
### Insert
![insert](https://github.com/danj98/dat250-assignments/blob/main/data/insert.png)
### Query
![query](https://github.com/danj98/dat250-assignments/blob/main/data/query.png)
### Update
![update](https://github.com/danj98/dat250-assignments/blob/main/data/update.png)
### Remove
![remove](https://github.com/danj98/dat250-assignments/blob/main/data/delete.png)
### Bulk write
![bulk](https://github.com/danj98/dat250-assignments/blob/main/data/bulk.png)

### Experiment 2 working
![exp2](https://github.com/danj98/dat250-assignments/blob/main/data/exp2.png)

### Own function
![own-func](https://github.com/danj98/dat250-assignments/blob/main/data/own-function.png)

## Map-reduce operation
### Map function
`var ownFunction = function() { emit(this.ord_date, this.price); };`

### Reduce function
`var ownReduce = function(keyDate, valuePrices) {return Array.sum(valuePrices); };`

This function will map total prices by date, which could be useful in order to 
get the total earnings for a given date.

## Pending issues
None
