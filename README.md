# data-science-beginner
Too much information to swallow about Data Science :weary:. Perhaps, writing these down out will clear my mind. But let me focus on Machine Learning :slot_machine: - one aspect, perhaps the most popular technique in Data Science.

## Motivation
Why should I study `machine learning`?
* As `programmer` :older_woman:, I will be out of the market very soon, if I don't master it
* As `innovator` :man_with_turban:, this is the magic tool to innovate a magic solution
* As `architect` :construction_worker:, uh, now is Software 2.0? And `machine learning` is the engine of it
* As `student` :girl:, ah, that's my past - but if you are student now, do you know that I need to look back my high school book again to remind myself about `Probabilistic`, `Linear Regression`, `Matrices Multiplication, Identities, Transpose`, etc. Student, you're one step ahead than me!

## High Level
* As `programmer`, you will draw a flowchart as the sceleton to write a program. In the flowchart, you would imagine the execution flow of the program, sprinkled with `if-then-else` logic, `loop`, etc. Writing a machine learning based program - you need to shift the way you think about writing normal program. It's different, continue reading!

* Given historical data (X1, Y1) -- read : input = X1, output = Y1. Machine learning technique will try to find `M`, such a way `X1 * M = Y1`. Once you find `M` - then you need to test the performance of M by another set of historical data (X2, Y2). If `X2 * M = Y2` then you have a perfect M -- but no, there is no perfect M, your target should only be `close-to-perfect` M.

* High school student who is learning matrices should be ahead of us, because X1, Y1, X2, Y2, M are all matrices. Why needs to be matrices? First, the input X is very likely to be multidimensional. Second, we need to have lot of sample records

### Give Me Example?!
Let's say we want to build house prediction price model.
What are the historical data we need to have?


## Typical / Basic Implementation

1. **Data Preparation** You must have `historical data`. And it should be a good number of `historical data`, perhaps hundreds or thousands. Example: to build a program to read handwriting, you need a collection of images of `handwriting` letters - and label each image with the letter. 

> Here, X1 = image, Y1=label. Our task is to find M, as such `X1 * M = Y1`, and this `M` should work with another set X2, as such `X2 * M = Y2`. 

2. **Data Sampling** X1 is it `image` or `matrices`? Matrices! You can't perform math calculation with images. Thus, we need to convert the image into number by doing `data sampling`

3. **Data Split** Supposed you have 1000 sample records. You need to split as two set, e.g. X1, Y1 as many as 750 records, and X2, Y2 as many as 250 records. You would then use X1 to build M, and use X2 to test how accurate is M. As mentioned above `if` M is perfect then X2 * M = Y2.

4. **Data Cleansing** There are cases where few of the historical data is creating problem instead of helping us in identifying the model. These are dirty data. Typical way to identify dirty data is by drawing them as graph, table, colored graphic. Once identified, we need to drop dirty data.

5. **Data Normalisation**




## Algorithm


