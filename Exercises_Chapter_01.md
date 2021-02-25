# Exercises

1.  Give a real-world example that requires sorting or a real-world example that requires computing a convex hull.

    The real world examples where sorting would be required are: 

    1.  Prices on bulk products in the bulk section of a grocery store
    2.  Calories/price in restaurant menu
    3.  Arrival times/Departure times of planes at an airport

2.  Other than speed, what other measures of efficiency might one use in a real-world setting?

    Other than speed, we need to worry about: 

    1.  Space requirement
    2.  Energy requirement

3.  Select a data structure that you've seen previously, and discuss its strengths and limitations

    I have seen array as a data structure. The strengths are: (1) quick indexing; (2) quick to add an element at the end of the array; (3) quick to remove last element. The weaknesses are: (1) adding or removing an element in the middle or in the front of an array steps lot of steps; (2) need to keep track of the length; (3) Searching takes long. 

4.  How are the shortest-path and traveling-salesman problems given above similar? How are they different? 

    Both problems are similar in the sense that both have the same objective: to go from point A to point B in the shortest possible way. However, the difference lies on the constraints imposed by the problem. For example, the traveling-salesman can only travel along lines that are straight and orthogonal to each other.

5.  Come up with a real-world problem in which only the best solution will do. Then come up with one in which a solution that is "approximately" the best is good enough.

    A closed-form solution would be the best solution. For example, finding pi to the 100th decimal point mathematically. An approximate problem involves a function that converges towards that answer but never gets to it. 