# Week 3

### `public static int[][] extractSubArray(int[][] inArray, int rowMin, int rowMax, int colMin, int colMax)`
extract sub array, given a 2-D array, and 2 ranges, produce a new array that is smaller and contains coppies of all the elements in the original at those locations. 
* input could be jagged
You can assume that the input will be such that the full sub-array will exist. 

### `public static boolean noneTrue(boolean[][] boolArray`
Given a boolean array, find if any of the inputs are true. 

### `public static boolean[][] gidOfMultiplesIgnoreValue(int[][] intArray, int ignoreVal)`
using the `gridOfMultiples` method from the week 2 lab (you should make a call to `searchAndPrint.gridOfMultiples`) using the given input, then if any of the positions in the returned boolean array are `true` and the corresponding value in the input has a value of `ignoreVal` then the boolean will be changed to `false`. 
