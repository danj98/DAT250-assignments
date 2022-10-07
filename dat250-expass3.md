# Expass3 report

## Technical problems
No technical issues were encountered while installing mongodb on Arch Linux as 
there was a precompiled binary available on the Arch User Repository.

## Screenshots

### Validation
![val](https://github.com/danj98/dat250-assignments/blob/main/assets/pgp-verified.png)
### Insert
![insert](https://github.com/danj98/dat250-assignments/blob/main/assets/insert.png)
### Query
![query](https://github.com/danj98/dat250-assignments/blob/main/assets/query.png)
### Update
![update](https://github.com/danj98/dat250-assignments/blob/main/assets/update.png)
### Remove
![remove](https://github.com/danj98/dat250-assignments/blob/main/assets/delete.png)
### Bulk write
![bulk](https://github.com/danj98/dat250-assignments/blob/main/assets/bulk.png)

### Experiment 2 working
![exp2](https://github.com/danj98/dat250-assignments/blob/main/assets/exp2.png)

### Own function
![own-func](https://github.com/danj98/dat250-assignments/blob/main/assets/own-function.png)

## Map-reduce operation
### Map function
`var ownFunction = function() { emit(this.ord_date, this.price); };`

### Reduce function
`var ownReduce = function(keyDate, valuePrices) {return Array.sum(valuePrices); };`

This function will map total prices by date, which could be useful in order to 
get the total earnings for a given date.

## Pending issues
None
