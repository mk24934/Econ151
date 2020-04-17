<span style="color:orchid"> +++ Laboratory assignment A +++ </span>
===================================================================

#### <span style="color:charcoal"> 1. Make a Data Frame with 2 columns and 3 rows (input any values you would like) </span>

``` r
df <- data.frame(x = c(1,2,3),
                 y = c(4,4,5))
```

#### <span style="color:charcoal"> 2. Find the mean of the first column, save the result in a variable called this\_mean </span>

``` r
this_mean <- (1+2+3)/3
```

#### <span style="color:charcoal"> 3. Test if this mean is correct. Place your answer below inside the test1 function below the r code chunk </span>

``` r
test1 <- function(value) {
  if (value == mean(df[,1]))
    text_spec('This test was passed!', color = "green")
  else
    text_spec('Test is not passed, please try again', color = "blue")
}
```

### Test 1: <span style="     color: green !important;">This test was passed!</span>
