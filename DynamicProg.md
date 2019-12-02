# Dynamic Programming and Backwards Induction

## World Series
>bet the game such that win and loss have the same payoff
## idea 
Backwards induction, start with the last game
```

```

## Toss coin three times
>toss the coins three times
## idea
Backwards induction, start with the last toss
```
Game3: 7/2
Game2: 3/6 * (7/2) + 1/6* (4 + 5 + 6)
Gmae1: ...
```

## NIM game
>be the first guy to hit 50
## idea
want to play, start backwards, choose the critical number
```
choose the number 6, 17, 28, 39, 50
```

## Flip the card and B+1, R-1
>what the expected payoff the game
## idea
```
E[r, b] = [
		  0; r = 0
		  r; b = 1,
	 	  max{ 0, r/(r+b)*[1 + E[r-1,b]] + b/(r+b)*[1 + E[r,b-1]] }
]
```