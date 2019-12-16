#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n)
  * This has a linear time complexity because the while loop runs for every value of n. 
  * This is optimal or at least pretty good.

b) 0(n log n)
* This has an outer loop that runs for every value of n, and an inner loop that runs for log(n).
* This is not good at all but it could be worse. 

c) 0(n)
* This is a linear time complexity, the function recurses once for every value of n.

## Exercise II

howSick(min=1, max=n):
	mid = n // 2
	if eggDrop(mid) == broken:
		howSick(1, mid)
	else:
		howSick(mid, n)

  *  You could start the first floor and drop an egg until it breaks, that would be 0(n) runtime. That breaks a lot of sick eggs. 
  *  Would be better to split the work into chunks, start with the middle floor, if it breaks you can get rid of half of n. That would make it 0(log n) runtime which is pretty dope.


