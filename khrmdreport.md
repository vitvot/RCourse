# Karens test markdown file

This is a test by Karen Hosking.     

Complex sums!!!

```
2+2
```

# Exercises

## Sub Exercises

* Compile the document for yourself.
* Fix the deliberate typo in the title.  What should be re-run when
  you "make". again.
* Change N to e.g. 1000 to see what happens when you "make".
* What happens when you change the plotting function (e.g. add
  xlab='...' to the hist call) -- what should be regenerated?
* Silence the first block of code by changing eval keyword to
  something obvious
  
# Random Matrix 
```
m <- matrix(rnorm(30), nrow = 6)   # random matrix
apply(m, 1, median)                # apply to all matrix
apply(m, 2, median)
```
