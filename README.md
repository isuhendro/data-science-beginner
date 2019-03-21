# data-science-beginner
Too many information to swallow about Data Science, maybe writing these out will clear my mind. But let me focus on Machine Learning - one aspect, perhaps the most popular technique in Data Science.

## Motivation
Why should I study `machine learning`?
* As `programmer`, I will be out of the market very soon, if I don't master it
* As `innovator`, this is the magic tool to innovate a magic solution
* As `architect`, uh, now is Software 2.0? And `machine learning` is the engine of it
* As `student`, ah, that's my past - but if you are student now, do you know that I need to look back my high school book again to remind myself about `Probabilistic`, `Linear Regression`, `Matrices Multiplication, Identities, Transpose`, etc. Student, you're one step ahead than me!

## High Level
* As `programmer`, you will draw a flowchart as the sceleton to write a program. In the flowchart, you would imagine the execution flow of the program, sprinkled with `if-then-else` logic, `loop`, etc. Writing a machine learning based program - you need to shift the way you think about writing normal program. It's different, continue reading!

* Given historical data (X1, Y1) -- read : input = X1, output = Y1. Machine learning technique will try to find `M`, such a way `X1 * M = Y1`. Once you find `M` - then you need to test the performance of M by another set of historical data (X2, Y2). If `X2 * M = Y2` then you have a perfect M -- but no, there is no perfect M, your target should only be `close-to-perfect` M.

* High school student who is learning matrices should be ahead of us, because X1, Y1, X2, Y2, M are all matrices. Why needs to be matrices? First, the input X is very likely to be multidimensional. Second, we need to have lot of sample records

### Give Me Example?!


## Typical Implementation

1. **Data preparation** You must have `historical data`. And it should be a good number of `historical data`, perhaps hundreds or thousands. Example: to build a program to read handwriting, you need a collection of images of `handwriting` letters - and label each image with the letter. 

> Here, X1 = image, Y1=label. Our task is to find M, as such `X1 * M = Y1`, and this `M` should work with another set X2, as such `X2 * M = Y2`. 

2. **Data sampling** X1 is it `image` or `matrices`? Matrices! You can't perform math calculation with images. Thus, we need to convert the image into number.





## Algorithm


