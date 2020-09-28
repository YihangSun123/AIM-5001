```python
import csv
# be sure to update the path below to reflect your own environment!!
# also be sure that the code is properly indented after you paste it!
with open('desktop/cars-sample35.txt') as csvfile:
 readCSV = csv.reader(csvfile)
 for row in readCSV:
     # print each row as read by the csv.reader function
     print(row)
```

    ['high', 'high', '2', '4', 'med', 'low', 'unacc']
    ['high', 'high', '4', 'more', 'small', 'high', 'acc']
    ['high', 'high', '4', 'more', 'big', 'low', 'unacc']
    ['high', 'low', '2', 'more', 'big', 'high', 'acc']
    ['vhigh', 'low', '3', '2', 'med', 'med', 'unacc']
    ['low', 'high', '2', '2', 'small', 'low', 'unacc']
    ['med', 'med', '4', 'more', 'med', 'high', 'vgood']
    ['low', 'low', '3', '2', 'big', 'med', 'unacc']
    ['vhigh', 'low', '2', '2', 'small', 'low', 'unacc']
    ['vhigh', 'high', '4', '4', 'med', 'low', 'unacc']
    ['low', 'low', '2', '2', 'med', 'med', 'unacc']
    ['vhigh', 'low', '4', 'more', 'small', 'high', 'acc']
    ['high', 'low', '2', '4', 'big', 'med', 'acc']
    ['low', 'vhigh', '3', 'more', 'big', 'low', 'unacc']
    ['high', 'low', '5more', '2', 'big', 'med', 'unacc']
    ['vhigh', 'high', '2', 'more', 'med', 'high', 'unacc']
    ['med', 'med', '2', '2', 'small', 'low', 'unacc']
    ['high', 'low', '5more', '4', 'med', 'high', 'acc']
    ['low', 'low', '3', 'more', 'med', 'high', 'vgood']
    ['low', 'low', '2', '2', 'big', 'med', 'unacc']
    ['med', 'high', '4', '2', 'big', 'high', 'unacc']
    ['low', 'low', '2', '2', 'small', 'high', 'unacc']
    ['vhigh', 'high', '5more', '4', 'med', 'med', 'unacc']
    ['med', 'vhigh', '2', '2', 'big', 'low', 'unacc']
    ['low', 'vhigh', '4', '4', 'big', 'low', 'unacc']
    ['vhigh', 'low', '3', 'more', 'big', 'low', 'unacc']
    ['med', 'vhigh', '3', '4', 'small', 'low', 'unacc']
    ['high', 'high', '3', '4', 'med', 'med', 'unacc']
    ['low', 'high', '5more', '2', 'big', 'low', 'unacc']
    ['med', 'high', '5more', '2', 'med', 'med', 'unacc']
    ['high', 'low', '3', '4', 'med', 'high', 'acc']
    ['high', 'vhigh', '5more', '4', 'med', 'med', 'unacc']
    ['low', 'low', '5more', '2', 'med', 'low', 'unacc']
    ['vhigh', 'vhigh', '4', '2', 'big', 'high', 'unacc']
    ['high', 'low', '3', '2', 'big', 'high', 'unacc']
    


```python
Price=[the first index of every list]
print(Price)
```


      File "<ipython-input-22-69f115d3d6bd>", line 1
        Price=[the first index of every list]
                   ^
    SyntaxError: invalid syntax
    



```python
import csv
# be sure to update the path below to reflect your own environment!!
# also be sure that the code is properly indented after you paste it!
with open('desktop/cars-sample35.txt') as csvfile:
 readCSV = csv.reader(csvfile)
 for row in readCSV:
     # print value in the first index of every list
     print (row[0])
```

    high
    high
    high
    high
    vhigh
    low
    med
    low
    vhigh
    vhigh
    low
    vhigh
    high
    low
    high
    vhigh
    med
    high
    low
    low
    med
    low
    vhigh
    med
    low
    vhigh
    med
    high
    low
    med
    high
    high
    low
    vhigh
    high
    


```python
import csv
# be sure to update the path below to reflect your own environment!!
# also be sure that the code is properly indented after you paste it!
with open('desktop/cars-sample35.txt') as csvfile:
 readCSV = csv.reader(csvfile)
 for row in readCSV:
     # print value in the second index of every list
     print (row[1])
```

    high
    high
    high
    low
    low
    high
    med
    low
    low
    high
    low
    low
    low
    vhigh
    low
    high
    med
    low
    low
    low
    high
    low
    high
    vhigh
    vhigh
    low
    vhigh
    high
    high
    high
    low
    vhigh
    low
    vhigh
    low
    


```python
import csv
# be sure to update the path below to reflect your own environment!!
# also be sure that the code is properly indented after you paste it!
with open('desktop/cars-sample35.txt') as csvfile:
 readCSV = csv.reader(csvfile)
 for row in readCSV:
     # print value in the thired index of every list
     print (row[2])
```

    2
    4
    4
    2
    3
    2
    4
    3
    2
    4
    2
    4
    2
    3
    5more
    2
    2
    5more
    3
    2
    4
    2
    5more
    2
    4
    3
    3
    3
    5more
    5more
    3
    5more
    5more
    4
    3
    


```python
import csv
# be sure to update the path below to reflect your own environment!!
# also be sure that the code is properly indented after you paste it!
with open('desktop/cars-sample35.txt') as csvfile:
 readCSV = csv.reader(csvfile)
 for row in readCSV:
     # print value in the fourth index of every list
     print (row[3])
```

    4
    more
    more
    more
    2
    2
    more
    2
    2
    4
    2
    more
    4
    more
    2
    more
    2
    4
    more
    2
    2
    2
    4
    2
    4
    more
    4
    4
    2
    2
    4
    4
    2
    2
    2
    


```python
import csv
# be sure to update the path below to reflect your own environment!!
# also be sure that the code is properly indented after you paste it!
with open('desktop/cars-sample35.txt') as csvfile:
 readCSV = csv.reader(csvfile)
 for row in readCSV:
     # print value in the fifth index of every list
     print (row[4])
```

    med
    small
    big
    big
    med
    small
    med
    big
    small
    med
    med
    small
    big
    big
    big
    med
    small
    med
    med
    big
    big
    small
    med
    big
    big
    big
    small
    med
    big
    med
    med
    med
    med
    big
    big
    


```python
import csv
# be sure to update the path below to reflect your own environment!!
# also be sure that the code is properly indented after you paste it!
with open('desktop/cars-sample35.txt') as csvfile:
 readCSV = csv.reader(csvfile)
 for row in readCSV:
     # print value in the sixth index of every list
     print (row[5])
```

    low
    high
    low
    high
    med
    low
    high
    med
    low
    low
    med
    high
    med
    low
    med
    high
    low
    high
    high
    med
    high
    high
    med
    low
    low
    low
    low
    med
    low
    med
    high
    med
    low
    high
    high
    


```python
import csv
# be sure to update the path below to reflect your own environment!!
# also be sure that the code is properly indented after you paste it!
with open('desktop/cars-sample35.txt') as csvfile:
 readCSV = csv.reader(csvfile)
 for row in readCSV:
     # print value in the seventh index of every list
     print (row[6])
```

    unacc
    acc
    unacc
    acc
    unacc
    unacc
    vgood
    unacc
    unacc
    unacc
    unacc
    acc
    acc
    unacc
    unacc
    unacc
    unacc
    acc
    vgood
    unacc
    unacc
    unacc
    unacc
    unacc
    unacc
    unacc
    unacc
    unacc
    unacc
    unacc
    acc
    unacc
    unacc
    unacc
    unacc
    


```python
# med of first index

print (row[0])
```

    high
    


```python
med price=[]

```


      File "<ipython-input-25-cd8b07f060a3>", line 1
        med price=[]
            ^
    SyntaxError: invalid syntax
    



```python
# number of passengers in med price
print (row(0)
```


      File "<ipython-input-30-d94d92e14ac7>", line 2
        print (row(0)
                     ^
    SyntaxError: unexpected EOF while parsing
    



```python
# high of first index
print (row[0])
```

    high
    


```python
# 2 of thired index and big of fifth index
print (row[0])
```

    high
    


```python

```
