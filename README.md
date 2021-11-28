# Programming-Assignment

HDip Data Analytics 2021 Programming for Data Analysis Assessment


*Submitted by*: Ciara O' Sullivan (Student Number: G00398379)

*Lecturer*: Brian McGinley

*Programming Language used*: Python

*Github respository at*: https://github.com/Cossie01/Programming-Assignment


1. Introduction

This README gives a quick overview of the Numpy Random Package in bullet form. This allows for the reader to get a quick snapshot of each topic. Each section is divided into seven parts based on what was outlined in the assignment brief. An in-depth analysis then can be found in the Numpy.random.ipynb file where I describe the overview of the overall basics and the history of the numpy random package, then I dig deeper into the numpy random package. From there, the notebook evaluated Simple Random data and Permutations function. Followed by an summary of five distribution and their everyday uses. This leads us to the use of seeds when generating pseudorandom numbers. 

In order to view the notebook you will need to download it from this repository and open it in Juypter. Jupyter notebook/lab is installed with the introduction of the Anaconda program. If unfamiliar with these programs, it is also possible to view a static version using my direct link to my git hub (Github link: https://github.com/Cossie01/Programming-Assignment). Furthermore, all images and reference can be located in a separate markdown file with the name References. I have also left some of my python code workings to show my continuous learning along the process in the notebook - Example Code.ipynb

This repository contains aspects of four tasks outlined in the Programming brief which includes the following:

Overall objectives of the assignment 
. Explain the overall purpose of the package.
. Explain the use of the “Simple random data” and “Permutations” functions.
. Explain the use and purpose of at least five “Distributions” functions.
. Explain the use of seeds in generating pseudorandom numbers.



2. The purpose of the Numpy Package.
-	Very fast application - faster to read less bytes of memory.
-	Removes the use of For loops to speeds up the process.
-	Uses single type for each element in the array. It has to be a an int, float or boolean.
-	Uses less memory, for python lists it saves each element in memory using pointers. Numpy by passes this using continuous memory.
-	Saves coding time. Numpy checks the data type speding up the process.
-   Searching for any element in the array is way quicker.

Numpy Random Package a sub package of the main Numpy Package

- Generates arrays containing a selection of random numbers.
- Ability to handle large volumes of arrays compared to the Python built in random function.
- With these large arrays, they can be manipulated and dissected as needed.
- Fast mathematical functions built in rather than creating loops.
- Can handle different types of data: int8, float64, bool, object, string.
- Probabilities can be placed into the functions.


3. Explain the use of the “Simple Random Data” and “Permutations” functions.

https://numpy.org/doc/stable/reference/random/generator.html Version 1.21 Manual was used in my assignment. 

Simple Random Data 

- Simple Random data allows the user to randomely pick an array of numbers by inputing the lowest, highest and the probability. 
- Data can be of different types whether it to be floats or integers within the range we decide. 
- It is useful to create random numbers to experiment on or to display different data distributions.
- With the Simple Random Data function it has four associated subfunctions (i)Integers, (ii) Random, (iii)Choice, (iv)Bytes. 
- All of which are explained and example code in the notebook Numpy.random.ipynb.

Permutations

- The permutation function allows the user to decide on how the data is to be shuffled or transposed. 
- A permutation is how the elements are arranged. They may have the same count of elements but they can have different variations. 
- Associated is three functions (i) Shuffle (ii)Permutation (iii)Permuted. 
- All of which again are explained further in the notebook Numpy.random.ipynb.



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
- Involved with statilitical analyses of counts or how many times an event occured.
- Flipping a coin, how many students passed an exam, boolean outcomes - how many was True shown, the success or failure of a drug in a clinical trial.
- A special version of the Binomial Distribution is the Bernoulli distribution where one single trial is counted and the probability is a success 1 or a failure 0.

Triangular Distribution
- The shape of this distribution is exactly as the name suggests its Triangular in shape.
- Effient and useful as we can often estimate the (a)minimum value (b) the max value we hope it should be (c) a random valuable that it is most likely to be
- This can determine the sales in a restaurant, lifetime of a laptop, votes in election, project planning.
- The area under the triangle = 1
- Simplistic representation of the probability distribution when limited sample data is available.
- Often 'best guess' when estimating the min and max points.
- When the distance of (a) and (c) widens, the densitiy of the values decrease.
- The location of the peak determines whether the pdf skews right or left, or if it is symmetrical.
![Triangular image](https://www.statology.org/wp-content/uploads/2021/01/trianglular1-1-768x620.png)


5. Explain the use of seeds in generating pseudorandom numbers.

![image](data:image/jpeg;base64,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)
 - explain the difference between old and new algothrim PG64. 
 - Computers are said to be Deterministic, meaning the actions are determined by a prescribed set of instructions.
 - Its hard for computers to create random numbers as they take input and produce and output. 
 - Best way around is to produce Pseudo Random numbers. 
 - With real random numbers the user cant retest the sequence.
 - Generating pseudo random numbers you do not need to store the long sequence of numbers only the seed. 
 - Pseudorandom numbers are easily repliciable, no other device needed and efficient.
 - Disadvance is that they are not actually random but appear to be somewhat random.
 - All sequence of pseudorandom numbers eventually repeat.
 - The seed can be determined as the encryption key. 
 - By reusing a seed we can reproduce the same data multiple times. 
 - The number of terms in sequence before it repeats is called the period.
 - Two methods of PRNG are the Middle Square Number and Linear Congruential Generator
 - Pseudorandom numbers are perfect for simulation or modelling in programs but not efficient for data encryption or gaming such as poker. 
 - The numpy package uses the PCG64 core generator. 
 
 
6. Conclusion

7. References