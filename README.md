# What is TOPSIS?

Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) originated in the 1980s as a multi-criteria decision making method. TOPSIS chooses the alternative of shortest Euclidean distance from the ideal solution, and greatest distance from the negative-ideal solution.

TOPSIS allow trade-offs between criteria, where a poor result in one criterion can be negated by a good result in another criterion. This provides a more realistic form of modelling

# Input Data

![image](https://user-images.githubusercontent.com/47549494/187021275-1dfae881-721b-4ffd-9dfb-47159c3c7fe2.png)

# How to Run the Code

Call the function topsis which has 3 parameter: topsis("file name where data is stored", "weight of parameter 1, weight of parameter 2,..,..,weight of parameter n", "+/- for parameter 1 ,+/- for parameter 2,+/- for parameter n")
Sum of weights should be one 
Choose '+' if parameter affects positively to ranking and choose '-' if paramter affects negatively to ranking

# Output Data

<img width="321" alt="Screen Shot 2022-08-27 at 3 09 50 AM" src="https://user-images.githubusercontent.com/47549494/187021415-72f6d68e-ea34-4c91-9fd7-b659feab4a59.png">


