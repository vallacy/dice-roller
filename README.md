# DnD Dice Roller

An R Script for rolling dice, including dice commonly used in DnD.

Roll a d4, d6, d8, d10, d12, or d20.

```R
#roll a d20 once
sample(1:20, 1, replace=T)
```

You can also create a histogram of your rolls to check that your samples are (roughly) uniformly distributed.

```R
#create an object called d20 that stores all of your rolls
d20 <- sample(1:20, 1, replace=T)
d20

#create a histogram of your rolls
hist(d20)
```
