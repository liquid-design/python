Non primitive data structures in python are Tuples,List,Dict and Set
# Tuples
     A tuple is a collection which is ordered and unchangeable. In Python tuples are written with round brackets.

### Example
    fruits=("Apple","Banana","Cherry","Dates")
    print(fruits)
### Output:
    ('Apple','Banana','Cherry','Dates')

### Nesting in tuples:
    t1 = ("Bmw","Audi")
    t2 = ("Honda","Maruti")
    t3 = (t1,t2)
    print t3
### Output:
    (('Bmw', 'Audi'), ('Honda', 'Maruti'))


### Repetition in Tuples:   
    t5=("hai",)*3
    print t5
### Output:
    ('hai', 'hai', 'hai')
