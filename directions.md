## Directions:

* In Sorts.java. You must implement the 3 sorting algortihms that we learned in classs. Please do not change the method signatures:

```
  public static void bubbleSort(int[] data) { }

  public static void selectionSort(int[] data)  { }

  public static void insertionSort(int[] data)  { }
```
  

* In Driver.java, you must randomly generate an array that will be sent as an argument when you call the sorting methods. If you want to reuse the same random array for all sorting algoritms you must generate copies of your array (Arrays.copyOf() or Objects.clone()).

* Do not use ArrayList.
  
* The methods in Sorts.java should be static and void.

* Your methods must not produce any output when they finish. Although using print statements during debugging is fine, they should be completely removed in your final submission.

* Once you create an array to test your method, make a copy of it. This allows you to compare the results of your sort with Java’s built-in sort (Arrays.sort(yourArray)), using the original array for your method and the copied array for the built-in method.
