# DSA
Learning Data Structures and algorithms concepts and solving problems on them in cpp

08/11/25:
done basic codes like Arrays basics like traversal,insertions,deletion and searching

striver's sheet:-
1)Reverse an Array:

using 2 pointers and single pointer approach
TC-O(n), SC-O(1)

2)Largest Element in an Array:

Brute force idea:sort an array and then element at n-1 position is the largest.
TC-O(Nlogn), SC-O(n)
Efficient idea:intialize  first element of array as the largest element n then run a loop..if any current element is larger than intialized then just update the largest element
Tc-O(N), SC-O(1)

3)Second largest element in an array:

Brute Force:sort the array and intialize largest to the n-1 th element n then sec lar to the -1 and then run a loop from n-2 th ele to the 1st if current element is not lar then it is the sec largest ele
TC-O(NLOGN+N), SC-O(1)
optimal:intialize lar to first element of arr n sec lar to -1,run a loop from 0 to n..if u find any current element greater than lar then sec lar would be the lar and just upadate lar to the current element and else if any current element is less then lar and greater than slar then just update slar
TC-O(N) SC-O(1)

4)Second smallest:
same logic folllows 

5)check if array is sorted:

 just run a loop and check if current ele is less than or equal to its next one if yes then return true else false
 TC:O(N) SC-O(1)



