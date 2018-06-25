# 1
data frame;
code: class(mtcars) OR is(mtcars, "data.frame")
# 2
precip is a vector;
code: dim(precip)
	  #if it was a 1D array, it would have a dimension
# 3
code: as(trees, "matrix")
# 4
Atlanta;
code: precip[14]
# 5
code: MultiArray <- c(trees, mtcars, precip)
# 6
Yes, precip has numeric data;
code: is(precip, "numeric")
# 7
mtcars[2, 7],
mtcars[2, "qsec],
mtcars["Mazda RX4 Wag", 7],
mtcars["Mazda RX4 Wag", "qsec"]
# 8
code: precip["Juneau"] <- 23
	   precip["Pheonix"] <- 46
	   precip["Sacramento" <- 12
# 9
No trees have more girth than volume.
# 10
2357.993;
code: A <- sum(trees[][2])
	  B <- sum(mtcars[6][])
	  C <- sum(precip[1:8])
	  D <- (C/B)
	  D + A
	  [1] 2357.993
