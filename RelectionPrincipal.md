# Reflection PRincipal

## Ballout Problem
>prob of no tie
## idea
num of paths that y > 0
path from 0 to n-m -> (m+n, n)
path hit -1 from 0 -> m-n-2 -> (m + n, m - 1)
```
p(y \geq 0) = 1 - ... = 1/(n + 1)
p(y > 0) = n/(m+n) * (n-1+1-m)/(n-1+1) = (n = m)/(n + m)
```
## Ticket Line
>prob no need to prepare changes
## idea
num of paths that y > 0
path from 0 to 0 -> (2n, n)
path hit -1, from 0 to -2 -> (2n, n - 1) 
```
p(X) = 1 - ... = 1 / (n + 1)
```