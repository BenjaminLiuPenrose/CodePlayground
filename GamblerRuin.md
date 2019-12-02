# Gambler's Ruin

## Gambler's Ruin
>start with i dollar and $LB, $HB, what is probability of ruin
## idea
```
p_i = p_{i + 1} * p + p_{i - 1} * q
```

## Balllout Problem
>probability of no tie given m > n votes yes and no
## idea
```
p_{n, m} = p_{n-1, m} * n / (m + n) + p_{n, m-1} * m / (m + n)
```

## Shark or Freedom
>Equal prob of moving in and out, then probability of freedom
## idea
```
p_i = p_{i + 1} * .5 + p_{i - 1} * .5
```