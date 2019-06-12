# Dictionary
    Dictionaries are Python’s implementation of a data structure that is more generally known as an associative array. A dictionary consists of a collection of key-value pairs. Each key-value pair maps the key to its associated value.
You can define a dictionary by enclosing a comma-separated list of key-value pairs in curly braces ({})

### Example
    dict={"Name":"Sajin","Age":42,"State":"Karnataka"}
    print dict
    
    # accesing values from dict using key
    print "Name : ",dict['Name']
    
    # updating values in dict
    dict['Age'] = 40
    print "After Updation : ",dict
    
    # adding new item to dictionary
    dict['Country'] = 'India'  
    print "After adding new item : ",dict
    
### Output
    {'Age': 42, 'Name': 'Sajin', 'State': 'Karnataka'}
    Name : Sajin
    After Updation : {'Age': 40, 'Name': 'Sajin', 'State': 'Karnataka'}
    After adding new item : {'Country': 'India', 'Age': 40, 'Name': 'Sajin', 'State': 'Karnataka'}
