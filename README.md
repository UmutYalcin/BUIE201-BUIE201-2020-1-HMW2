# Homework 2

Use functions FindSimpleWithRangeForLoop and FindBinarySearch from the lecture.

1. Modify the TestVectorSet function so that you report the time it takes to create the vector and the set; and running the "find" functions.
2. Modify the main function so that you perform the test for sz values 1000, 10000, 100000, 1000000, 10000000.
3. For each sz value, perform the test for 10 randomly generated ValueToFind values between 0 and sz-1. Do not forget to randomize your seed value for the rand function.
4. Generate a report that lists the average performance of each "find" function for each sz value. Report may look as follows:

|Function | 1000 | 10000 | 100000 | 1000000 | 10000000|
|----| ---- | ---- | ---- | ---- | ----|
|Vector construct |2031.8 |18686.2 |191695.6 |1860908 |18494894 
|Set construct |26386.8 |332250.9 |3780011 |42011138 |485179701.5 
|FindSimpleWithRangeForLoop |11.8 |87.5 |259.6 |225.6 |231.4 
|FindBinarySearch |8.8 |13.7 |13.2 |12.2 |13.2 
|Set find |27.8 |38.3 |55.6 |78.1 |58.5 
