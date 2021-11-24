# Programming-Assignment

HDip Data Analytics 2021 Programming for Data Analysis Assessment


*Submitted by*: Ciara O' Sullivan (Student Number: G00398379)
*Lecturer*: Brian McGinley
*Programming Language used*: Python
*Github respository at*:https://github.com/Cossie01/Programming-Assignment


1. Introduction
This README describes the overview of the overall basics and the history of the numpy random package, then digs deeper into the numpy random package. From there, it evaluated Simple Random data and Permutations function. Followed by an summary of five distruibution and their everyday uses. This leads us to the use of seeds when genetating pseudorandom numbers. 

Alongside the README, I examine and show my workings in a single jupyter notebook - called Numpy.random.ipynb 
In order to view the notebook you will need to download it from this repository and open it in Juypter. Jupyter notebook/lab is installed with the introduction of the Anaconda program. If unfamiliar with these programms, it is also possible to view a static version using my direct link to my git hub (Github link:https://github.com/Cossie01/Programming-Assignment) Furthermore, all images and reference can be located in a seperate markdown file with the name References. I have also left some of my python code workings to show my continuous learning along the process in the notebook - Example Code.ipynb

This repository contains aspects of four tasks outlined in the Programming brief which includes the following:

- 
Overall objectives of the assignment 
. Explain the overall purpose of the package.
. Explain the use of the “Simple random data” and “Permutations” functions.
. Explain the use and purpose of at least five “Distributions” functions.
. Explain the use of seeds in generating pseudorandom numbers.


2. 2.	The purpose of the Numpy Random Package.
-	Very fast application - faster to read less bytes of memory.
-	Removes the use of For loops to speeds up the process.
-	Uses single type for each element in the array. It has to be a an int, float or boolean.
-	Uses less memory, for python lists it saves each element in memory using pointers. Numpy by passes this using continuous memory.
-	Saves coding time. Numpy checks the data type speding up the process.  


3. Explain the use of the “Simple random data” and “Permutations” functions.

https://numpy.org/doc/stable/reference/random/generator.html Version 1.21 Manual

4. Explain the use and purpose of at least five “Distributions” functions

Normal distribution

- often data in statiscs is described as being 'normal' which refers to the frequency of the data, this can be man-made or natural. 
- Natural examples would be blood pressure values, height, weight, temperature outside.
- Man- made examples would be sales data, financial end of year values, quality values.
- Values or data points tend to accumalate around the mean or center of the curve.
- It contains a lower tail and upper tail and the mean in middle. 
- everything under the curve is the called the probability area and equals to one. 
- the curve is symmetrical and theoritically it is equal on both sides if folded in half.
- the top of the curve is also known as mode, median as well as the mean. 
- the shape of the curve is influenced by the standard deviation.
- Standard deviation is the measure how spread out the values are and is represented by the greek letter sigma 
- Standard deviation is associated with the 68-95-99.7 rule. This suggests that 68% of the data will lie within 1 standard deviation of the mean, 95% of the    data will lie within 2 standard deviation of the mean and 99.7% of the data will lie within 3 standard deviation of the mean. 
- PDF (Probility Density Function)
- graph is unimodal (one peak)
- total area under the curve is 1 

Exponential Distribution

- inverse of the Poisson process
- Poisson example; the number of cars passing a toolgate in one hour: events per single unit of time
- Exponential example; the number of hours between car arrivals: time per single event
- Events must occur at a constant rate 
- events must be independant of each other
- PMF (Probability Mass Function) for Poisson
- PDF for Exponential
- CDF (Cummulative Density Function)

Binomial Distribution
- Involved with statitical analyses of counts or how many times an event occured.
- Flipping a coin, how many students passed an exam, boolean outcomes - how many was True shown, the success or failure of a drug in a clinical trial.

5. Explain the use of seeds in generating pseudorandom numbers.
 - explain the difference between old and new algothrim PG64. 
 
6. Conclusion

7. References