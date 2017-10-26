# Statistics

__*Todo:*__

* *Add formulars*

* *Add python examples*


</br>
## Population

A population includes ALL elements from a dataset.
</br>

## Sample

A sample includes a subset of the population.

</br>
## Mean

Mean also known as average is the sum of all numbers divided by the count of numbers.

</br>
## Median

Median is the middle value in a list of numbers. To find the median your list must bw sorted. If the list contains an un-even amount of numbers the median is simply the middle number. If the length of the lidt is even then you find the median by claculating the mean or average of the 2 middle numbers.

</br>
## Mode

The mode is the value value that occurs most often. If ni number in the list is repeated, then there is no mode.

</br>
## Range

The range is simply the difference between the largest and the samllest number in a dataset.

</br>
## Variance

The variance refers to the spread of a dataset - how far apart the numbers are in relation to the mean. Also refered to as the `squared differences` - because you sum up the individual differences squared. 

--- show formular ---

One important question one might ask is why do we square each difference? Well, we do this to rule out negative numbers. When you take any number x and subtract the mean of all x's, this result could very much turn out negative. When summing up all the differences - without squarring them - the numbers could cancel out each other beacuse the numbers contain both positive and negative numbers. This will lead to a false impression of the data. Thus, we square the differences to keep all numbers positive. 

The variance itself does not say much about anything. It's hard to compare the variance to the original datapoints and make any conlusions. To do this we might look into Standard Deviation.

This is an example to picture variance in a simple graph.

-- show example graph ---

</br>
## Standard Deviation

Standard deviation is like an extension to the variance. To recap, variance sums up all the squared differences. But because we square all the differences to cancel out negative numbers, the final result will be in a different and bigger scale than the original numbers - meaning that it is very hard to draw meaning from the variance. 

-- show formular ---

Standard deviation comes to the resque by simply taking the square root of the variance. This basically cancels out the previous step where we squared the differences, and leaves us with the average spread of each individual datapoint - the standard deviation.

</br>
## Covariance

A covariance refers to the measure of how two random values (x, y) will change together and is used to calculate the correlation between variables. For instance, in a graph if x grows will y grow as well. If that is the case then we say there is a positive corelation between x and y.

-- show formular ---

Thus, you can use covariance as a measure of positive or nagtive corelation between 2 variables (x, y). If a covariance is greater than zero the relation is positive. If the covariance is less than zero the relation is negative. 

Much like variance, the covariance value itself does not say much about the data. You can't for instance compare two different covariances and conclude that because the first is a lot bigger than the other, the first has a bigger positive relation. That would be a fault. 


To understand this, lets take an example

Good youtube video describing this: https://www.youtube.com/watch?v=KDw3hC2YNFc

--- show positive graph example ---

In a positive relationship between x and y:

If x > x_hat -> + && + --> + 
If x > x_hat -> - && - --> + 

So the covariance between x and y when theres is a positive relationship between x and y will be positive.

--- show positive graph example ---

In a negative relationship between x and y:

If x > x_hat -> + && - --> - 
If x > x_hat -> - && + --> -

So the covariance between x and y when theres is a negative relationship between x and y will be negative.

In conclusion what you can derive from a covariance is whether a set of datapoints are either positively or negatively related to one another. What a covariance does NOT say is the magnitude of the relation - in other words HOW positively or negatively related are the data.

</br>
## Correlation

Like covariance, correlation refers to the measure of how two random values (x, y) will change together and is used to calculate the correlation between variables. If corrlealtion describes IF there is a positive or negatice relation, then correlation describes the SIZE of the realtion (the magnitude of the realtion). So the main difference between covariance and corelation is that a correlation is nomalized (scaled down) to a range bewtween -1 and +1, where -1 means 100% negtaive realtion and +1 one means a 100% positive relation. Zero indicates NO relation between the values x and y in a dataset.

--- show formular ---
