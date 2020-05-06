# Interval-Splitting_Project

Problem Description:-
  Input- a set of real numbers in a data structure in random order(here, we are reading a file)
       - any real number (epsilon)
       
We have to segreagte these input points in seperate intevals (eg, [a,b],[c,d]). Segregation should be such that every consecutive  point in [a,b] belonging to the input file should be at a distance less than or equal to epsilon (given). When a point (here, for eg, c) is at a distance greater than epsilon from the upper limit of the previous interval (here, b) a new interval should begin (here, [a,b], [c,d])
  Output- set of intervals (eg. [a,b], [c,d])
  
