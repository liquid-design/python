# Lists
     The list is a most versatile datatype available in Python which can be written as a list of comma-separated values (items) between square brackets. Important thing about a list is that items in a list need not be of the same type.
Creating a list is as simple as putting different comma-separated values between square brackets

## Example
    list1 = [10,20,30,40]
    list2 = ['Redmi','Samsung','htc']

Similar to string indices, list indices start at 0, and lists can be sliced, concatenated and so on.

### List operations
    list3 = [100,200,300,400,500]
    # accessing values from list
    print "Value at the first position is : ",list3[0]
    # updating values in the list
    list3[1] = 250
    print "List after Updating : ",list3
    # deleting elements from the list
    del list3[2]
    print "List after deletion : ",list3
    #adding values to list
    list3.append(600)
    list3.append(700)
    print "List after adding new elements : ",list3
### Output
    Value at the first position is : 100
    List after Updating : [100,250,300,400,500]
    List after deletion : [100,250,400,500]
    List after adding new elements : [100,250,400,500,600,700]
    
