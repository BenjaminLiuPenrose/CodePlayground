# Derangement Number

## Application Letter
> Match application letters with person
## idea
known #n will choose #k, conditioned on #k choice 
```
a_n = a_{n - 1} * (n - 1) +
	  a_{n - 2} * (n - 1)
```

## Mans and Hats
> prob of man not having their hats
## idea
known #1 will choose #k, conditioned on #k choice 
```
p_n = (n-1)/n * [
	  p_{n-1} +
	  p_{n-2} * (1 / n-1)
]
```

## Airline Seats, Grandma Problem
> airplane seats, conclusion p = .5
## idea
conditioned on #1 passenger choose 
```
p_n = 1 / n  * 1 +
	 1 / n * 0
     (n - 2) / n * p_{n - 1}
```
