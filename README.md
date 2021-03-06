# Programming-Assignment

HDip Data Analytics 2021 Programming for Data Analysis Assessment


*Submitted by*: Ciara O' Sullivan (Student Number: G00398379)

*Lecturer*: Brian McGinley

*Programming Language used*: Python

*Github respository at*: https://github.com/Cossie01/Programming-Assignment


# 1. Introduction

This README gives a quick overview of the Numpy Random Package in bullet form. This allows for the reader to get a quick snapshot of each topic. Each section is divided into seven parts based on what was outlined in the assignment brief. An in-depth analysis then can be found in the Numpy.random.ipynb file where I describe the overview of the overall basics and the history of the numpy random package, then I dig deeper into the numpy random package. From there, the notebook evaluated Simple Random data and Permutations function. Followed by an summary of five distribution and their everyday uses. This leads us to the use of seeds when generating pseudorandom numbers. 

In order to view the notebook you will need to download it from this repository and open it in Juypter. Jupyter notebook/lab is installed with the introduction of the Anaconda program. If unfamiliar with these programs, it is also possible to view a static version using my direct link to my git hub (Github link: https://github.com/Cossie01/Programming-Assignment). Furthermore, all images and reference can be located in a separate markdown file with the name References. I have also left some of my python code workings to show my continuous learning along the process in the notebook - Example Code.ipynb

This repository contains aspects of four tasks outlined in the Programming brief which includes the following:

## Overall objectives of the assignment 
*Explain the overall purpose of the package.*

*Explain the use of the “Simple random data” and “Permutations” functions.*

*Explain the use and purpose of at least five “Distributions” functions.*

*Explain the use of seeds in generating pseudorandom numbers.*




# 2. The purpose of the Numpy Package.
-	Very fast application - faster to read less bytes of memory.
-	Removes the use of For loops to speeds up the process.
-	Uses single type for each element in the array. It has to be a an int, float or boolean.
-	Uses less memory, for python lists it saves each element in memory using pointers. Numpy by passes this using continuous memory.
-	Saves coding time. Numpy checks the data type speding up the process.
-   Searching for any element in the array is way quicker.

## Numpy Random Package a sub package of the main Numpy Package

- Generates arrays containing a selection of random numbers.
- Ability to handle large volumes of arrays compared to the Python built in random function.
- With these large arrays, they can be manipulated and dissected as needed.
- Fast mathematical functions built in rather than creating loops.
- Can handle different types of data: int8, float64, bool, object, string.
- Probabilities can be placed into the functions.


# 3. Explain the use of the “Simple Random Data” and “Permutations” functions.

https://numpy.org/doc/stable/reference/random/generator.html Version 1.21 Manual was used in my assignment. 

## Simple Random Data 

- Simple Random data allows the user to randomely pick an array of numbers by inputing the lowest, highest and the probability. 
- Data can be of different types whether it to be floats or integers within the range we decide. 
- It is useful to create random numbers to experiment on or to display different data distributions.
- With the Simple Random Data function it has four associated subfunctions (i) Integers, (ii) Random, (iii) Choice, (iv) Bytes. 
- All of which are explained and example code in the notebook Numpy.random.ipynb.

## Permutations

- The permutation function allows the user to decide on how the data is to be shuffled or transposed. 
- A permutation is how the elements are arranged. They may have the same count of elements but they can have different variations. 
- Associated is three functions (i) Shuffle (ii) Permutation (iii) Permuted. 
- All of which again are explained further in the notebook Numpy.random.ipynb.



# 4. Explain the use and purpose of at least five “Distributions” functions

## Uniform distribution

- In statistics, uniform distribution can either be continuous or discrete. 
- Each will have the same amount of outcomes and the probability of each outcome will be the same. 
- Discrete has finite values for example rolling a dice: 6 possible outcomes [1,2,3,4,5,6]. You would not see 3.5 dots on a dice!
- Continuous on the other hand are able to work with these floats eg 1.2, 6.77, 0.334 etc. 
- Using a deck of card in a game = discrete uniform distribution, as each player has an equal chance of pulling a heart as they do a spade.
- Another real world example would be in a store room where a stock take should be taken and then with this distribution it can help guide the manager on how best to utilize the floor space.
- Also used in risk assessments in the Monte Carlo simulation programs.
- For this distribution, three parameters are passed through; a lower bound and high bound and the size of the array.


![Uniform](https://www.thoughtco.com/thmb/_AlCiAafNKlA4ttjmkNMsejrmdE=/1464x524/filters:fill(auto,1)/uniform-5814e2025f9b581c0baef8de.jpg)

## Normal distribution

- Often data in statics is described as being 'normal' which refers to the frequency of the data, this can be man-made or natural. 
- Natural examples would be blood pressure values, height, weight, temperature outside.
- Man- made examples would be sales data, financial end of year values, quality values.
- Values or data points tend to accumulate around the mean or center of the curve.
- It contains a lower tail and upper tail and the mean in middle. 
- Everything under the curve is the called the probability area and equals to one. 
- The curve is symmetrical and theoretically it is equal on both sides if folded in half.
- The top of the curve is also known as mode, median as well as the mean. 
- The shape of the curve is influenced by the standard deviation.
- Standard deviation is the measure how spread out the values are and is represented by the Greek letter sigma.
- Standard deviation is associated with the 68-95-99.7 rule. This suggests that 68% of the data will lie within 1 standard deviation of the mean, 95% of the data will lie within 2 standard deviation of the mean and 99.7% of the data will lie within 3 standard deviation of the mean. 
- Commonly categorised as unimodal (one peak).
- The total area under the curve is equal to 1.


![image](https://th.bing.com/th/id/OIP.Vux5bpcQNbRv8TmZAUHVkwHaDa?pid=ImgDet&rs=1)


## Exponential Distribution

- Inverse of the Poisson process.
- Poisson example; the number of cars passing a tollgate in one hour: events per single unit of time
- Exponential example; the number of hours between car arrivals: time per single event
- Events must occur at a constant rate and must be independent of each other.
- It is mentioned that this is a continuous probability distribution used to predict the time to wait before the event occurs again.
- It must contain two parameter (i) Scale; the inverse rate (ii) Size; the array size.
- Example of this is amount of time a laptop battery lasts, length of time in minutes of a phone call, value of change in your pocket over time.

![image](https://www.efunda.com/math/distributions/images/ExpDistPlot.gif)

## Binomial Distribution

- Involved with statistical analyses of counts or how many times an event occurred.
- Flipping a coin, how many students passed an exam, Boolean outcomes - how many was True shown, the success or failure of a drug in a clinical trial.
- The test must accomplish repeated trials, outcome; yes or no, 1 or 0, the probability of success is constant and they are independent of each other.
- A special version of the Binomial Distribution is the Bernoulli distribution where one single trial is counted and the probability is a success 1 or a failure 0.
- If the sample is large enough the shape of the curve could look similar to a normal distribution.
- Normal distribution is a continuous data that is symmetrical, while binomial has an finite sample. 
- This distribution can be found in new drug experiments whether a drug has cured the patient Yes of No, Success or Failure. Number of crime cases that have been resolved or unsolved.


![image](https://dataatomic.com/post/2019-10-28-an-intuitive-example-for-a-binomial-distribution_files/figure-html/install%20packages-1.png)

## Triangular Distribution

- The shape of this distribution is exactly as the name suggests its Triangular in shape.
- Efficient  and useful as we can often estimate the (a)minimum value (b) the max value we hope it should be (c) a random valuable that it is most likely to be
- This can determine the sales in a restaurant, lifetime of a laptop, votes in election, project planning.
- The area under the triangle = 1
- Simplistic representation of the probability distribution when limited sample data is available.
- Often 'best guess' when estimating the min and max points.
- When the distance of (a) and (c) widens, the density of the values decrease.
- The location of the peak determines whether the pdf skews right or left, or if it is symmetrical.

![Triangular image](https://www.statology.org/wp-content/uploads/2021/01/trianglular1-1-768x620.png)


# 5. Explain the use of seeds in generating pseudorandom numbers.

![image](https://quotefancy.com/media/wallpaper/3840x2160/5413652-Donald-Knuth-Quote-Random-numbers-should-not-be-generated-with-a.jpg)

 - Computers are said to be Deterministic, meaning the actions are determined by a prescribed set of instructions.
 - It is hard for computers to create random numbers as they take input and produce and output. 
 - Best way around is to produce Pseudo Random numbers. 
 - With real random numbers the user cant retest the sequence.
 - Generating pseudo random numbers you do not need to store the long sequence of numbers only the seed. 
 - Pseudorandom numbers are easily replicable, no other device needed and efficient.
 - Disadvantage is that they are not actually random but appear to be somewhat random.
 - All sequence of pseudorandom numbers eventually repeat.
 - The seed can be determined as the encryption key. 
 - By reusing a seed we can reproduce the same data multiple times. 
 - The number of terms in sequence before it repeats is called the period.
 - Two methods of PRNG are the Middle Square Number and Linear Congruential Generator
 - Pseudorandom numbers are perfect for simulation or modelling in programs but not efficient for data encryption or gaming such as poker. 
 - The newest version of the numpy package uses the PCG64 core generator. 
 
 
# 6. Conclusion

In conclusion, this research has examined the functions and uses of numpy.random package. Fundamentally, this tool is efficient at manipulating large volumes of data by arranging them into N-darrays. From there, the user can slice, index, sort and search through as well as many other operations as mentioned above. In the world of data science and statistics, the ability to produce random numbers to test your code or manipulate data or shuffle a training set is very important. 

The numpy package is also open sourced so it is always being updated so the newest code can be used. While the official documentation of numpy can be verbose, there are many other websites that will explain it more straightforward, some of which are found in the reference notebook. In the numpy.random notebook, I hoped I have explained how random numbers are created, how they are shuffled and how the random numbers can be shown in various distribution. Finally, I demonstrated the use of seeds and how they impact the sequence of pseudo numbers. I believe I will no doubt use this in other assignments alongside my work projects. 

# 7. References

These can be found in the markdown file called References.
