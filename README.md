# My findings
a) I observed that, in this case, using recursion based technique is more time consuming than iterative based. Isertion sort (iterative based) took less time to sort the given array. Time complexity of insertion sort lies between O(n) (best case) and O(n^2) (worst case), depends on how much sorted given array is. Time complexity of Merge sort is O(nlogn), it could be possible that given array is alredy sorted to some extend, so the time taken by insertion sort is less than merge sort.

b) In this lab I have observed inheritence and polymorphism of classes. 
Inheritance is the capability of one class to derive or inherit the properties from another class. It provides reusability of a code. We don’t have to write the same code again and again.
Polymorphism means having many forms. In programming, polymorphism means the same function name being used for different types.	
In our first problem,I have used inheritence, when I created an io.TextIOWrapper class object and used write method, which it inherents from IOBase class. In second problem, I observed that different classes have same method, DataFrame and GeoDataFrame classes have head() method, which is nothing but polymorphism. Also, inheritence as well as polymorphism is observed when I used plot() method for GeoSeries and GeoDataFrame classes, which they both inherits from matplotlib.axes.Axes class.
