# The-arrSelectSort-Function
 For startScan is set to the values 0 up to (but not including) the
next-to-last subscript in arr
Set index variable to startScan
Set minIndex variable to startScan
Set minElem pointer to arr[startScan]
For index variable is set to the values from (startScan + 1) through
the last subscript in arr
If *(arr[index]) is less than *minElem
Set minElem to arr[index]
Set minIndex to index
End If
End For
Set arr[minIndex] to arr[startScan]
Set arr[startScan] to minElem
End For
