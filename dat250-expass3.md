# Expass3 report

## Technical problems
No technical issues were encountered while installing mongodb on Arch Linux as 
there was a precompiled binary available on the Arch User Repository.

## Screenshots

### Validation
![val]()
### Insert
![insert]()
### Query
![query]()
### Update
![update]()
### Remove
![remove]()
### Bulk write
![bulk]()

### Experiment 2 working
![gpg]()

### Own function
![own-func]()

## Map-reduce operation
### Map function
`var ownFunction = function() { emit(this.ord_date, this.price); };`

### Reduce function
`var ownReduce = function(keyDate, valuePrices) {return Array.sum(valuePrices); };`

This function will map total prices by date, which could be useful in order to 
get the total earnings for a given date.

## Pending issues
None
