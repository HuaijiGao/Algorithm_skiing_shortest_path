# skiing_shortest_path

Alex loves skiing and, in order to keep gaining speed, they prefer to always ski downwards. Alex collected
the measured altitude of an area that they plan to go next month, represented using an array of size n by
n. An example with n = 4 is given below:

<img width="225" alt="image" src="https://user-images.githubusercontent.com/19381768/197388771-22475536-551c-4ecf-9ec0-7438015f55fb.png">

Alex can start skiing from any cell and move to an adjacent cell on the right, left, up or down (no diagonals),
anytime as needed. They will always ski towards an adjacent cell with a strictly lower altitude. In
the above example, one possible skiing path is 50−23−15−12−4. Of course, 50−33−28−23−15−12−4
is another one, and in fact the longest possible one.

# pseudocode questions
(a) Write a function LongestSkiingPath(M[0..n − 1][0..n − 1]) in pseudocode, which takes a 2-D array
representing for the measured altitude of an area as input and calculates the number of cells involved
in the longest path, using Dynamic Programming. Using the above example, your algorithm should
return 7.

(b) What’s the time complexity of your algorithm? Briefly justify your answer.
