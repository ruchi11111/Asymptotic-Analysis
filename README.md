The aim of this project is to analyse three sorting algorithms, selection sort, insertion sort and quick sort, based on different size of data and their corresponding running time. This implementation is prepared in the file sorting.py which includes three sorting functions: selection_sort(), quick_sort() and insertion_sort() whereas the functions like swap(), partition() and quickSortHelper() are functions to implement quick sort successfully.Fig. 1 depicts a sample for how the output looks for insertion sort with sorted array of 10,000 instances.

              ![picturefig1](C:\Users\Asus\Desktop\ASYFIG1.png)


From the results noted in SortingTimes.csv the algorithm that performs the best on data less than 1000000 is insertion sort but only for the case of sorted and constant arrays whereas quick sort performs the best for the mentioned data in case of random array input. Insertion sort again works the best for data for range 106 to 109 for sorted and constant input arrays and quick sort works best for the mentioned data range for random input array. For selection sort, the complexity as per the graph (Fig. 3) is O(n2). For input range of 109, the complexity of insertion sort results as O(n2) and the quick sort results in memory error for all cases. Hence, selection sort takes the longest sorting time for all three kinds of array and insertion sort takes the least time for sorted and constant arrays and the complexity for both cases is O(n) according to the graph (Fig. 4). Quick sort takes the least time for sorting a random input array and hence complexity becomes O(n lgn) as seen in the graph (Fig. 5). 


A noticeable case where the quick sort shows recursion error (Fig. 2) while sorting an array of constant input array because of the default recursion depth set to 1000. Even after
increasing the recursion depth, the algorithm for constant input array does not work as expected. 
