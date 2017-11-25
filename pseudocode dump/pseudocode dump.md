#Pseudocode Dump

Pseudocodes that express Ethereum's working parts operationally as objects.


##Transaction Receipt
```
class transactions_receipt
	group=tuple
	size=4
	members={
		transaction(poststate) 
		total_gas(used)
		log_entries
		logs(bloom_filter)
		}
```

###Logs Set
```
class logs_set
	group=set
	size=n+1
	members={
	log_entry(1)
	log_entry(2)
	log_entry(3)
	log_entry(n)
	forall(logs_in_set)
	}
```

###Log Entry
```
class log_entry
	group=tuple
	size=3
	members={
		logger(address)
		log_topics(series)
		bytes_data(n)
		}
```
###Logs Bloom
```

```





