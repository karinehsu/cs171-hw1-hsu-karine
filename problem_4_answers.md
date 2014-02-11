1. The domain() function is the data range upon which the scale is calculated. What does d3.selectAll("tbody tr")[0].length-1 mean?


d3.selectAll("tbody tr") first selects all the table rows in the table's body and gives it to us in an array. The [0] allows us to access the HTML elements associated with the rows. The .length -1 returns the index of the last element in the array.  

2. Add the snippet in your code. Describe, in words, what the following function calls return: color(0), color(10) and color(150)?

color(0) returns "#ff4500", the color orange red
color(10) returns "#f25e26", brighter orange
color(150) returns "#42ffff", light turquoise color


3.If the array passed to domain() was the minimum and maximum rate values, how would that change the scale? In what situations would this be appropriate?

In the code snippet, orange red corresponds to the range of 0, and silver corresponds to the last value in the range. If we passed the minimum and maximum rate values, this would change most of our colors to return orange-red colors because our rates in the table given are around 2.6 - 9.0, closer to 0 than the last index of the array. This situation would be appropriate because it means the maximum and minimum rate values would correspond directly with the code snippet's min and max values for the colors. 
