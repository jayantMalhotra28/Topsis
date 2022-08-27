# What is TOPSIS?

Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) originated in the 1980s as a multi-criteria decision making method. TOPSIS chooses the alternative of shortest Euclidean distance from the ideal solution, and greatest distance from the negative-ideal solution.

TOPSIS allow trade-offs between criteria, where a poor result in one criterion can be negated by a good result in another criterion. This provides a more realistic form of modelling

# Input Data

<img width="300" alt="Screen Shot 2022-08-27 at 3 02 45 AM" src="https://user-images.githubusercontent.com/47549494/187021582-c1c1be8f-f590-4fb8-8305-b08082c6f510.png">

# How to Run the Code

1) Call the function topsis which has 3 parameter: topsis("file name where data is stored", "weight of parameter 1, weight of parameter 2,..,..,weight of   parameter n", "+/- for parameter 1 ,+/- for parameter 2,+/- for parameter n")

2) Sum of weights should be one 

3) Choose '+' if parameter affects positively to ranking and choose '-' if paramter affects negatively to ranking

# Output Data

<img width="300" alt="Screen Shot 2022-08-27 at 3 13 21 AM" src="https://user-images.githubusercontent.com/47549494/187021550-02ce6b32-4865-48b1-8ff6-008d1631048a.png">


