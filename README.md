# HashTable
A hash table is a data structure that is used to store keys/value pairs.
This particular hashtable is implemented using doubly linked list. It has total of 15 methods.

- insertFirst
- insertLast
- insertAtIndex
- getValueByIndex
- getValueByKey
- deleteFirst
- deleteLast
- deleteByVal
- deleteByIndex
- deleteByKey
- PrintkeyValues
- printValues
- printKeys
- PrintReverse
- length

### insertFirst:
It takes **two** arguments **key** and **value** and stores them at the very begining of the table. If the key already exists, it 
**replaces the current value of the key with the new value**, without changing it's index.

### insertLast:
It takes **two** arguments **key** and **value** and stores them at the very **last index** of the table. If the key already exists, it 
**replaces the current value of the key with the new value**, without changing it's index.

### insertAtIndex:
It takes **three** arguments index, key and value and stores the value at the **index provided by the user** by shifting the reaming 
values 1 index ahead.It also checks for the key in the table. If the **key already exists**, it **replaces it's current value with 
the new value** without changing it's index.It also checks, if the index provided by the user is greater then the length of the 
table, it returns "**Index not reachable**".

### getValueByIndex:
It takes **one** argument **index** and returns the value stored at the index.If the provided index is invalid it returns "**index out of range**".

### getValueByKey:
It takes **one** argument **key** returns the value associated with the key.If the provided key is invalid, it returns "**Key not found**".

### deleteFirst:
It deletes the **first key/value** pair stored in the table. It takes **no** arguments.

### deleteLast:
It deletes the **last key/value** pair stored in the table. It takes **no** arguments.

### deleteByVal:
It takes one argument **value** and deletes the **first occurence of the provided value**. if the value is not present in the table, 
it returns "**Item not found**".

### deleteByIndex:
It takes one argument **index** and **deletes the key/value pair at the provided index**. If the provided index is invalid, it returns "**Index not found**".

### deleteByKey:
It takes one argument **key** and **deletes the key/value pair at the provided key**. If the provided key is invalid, it returns "**Key not found**".

### PrintkeyValues:
It **prints** the entire table in key/value pairs. It takes **no** argumnets.

### printKeys:
It **prints** all the keys stored in the table. It takes **no** argumnets.

### printValues:
It **prints** all the values stored in the table. It takes **no** argumnets.

### PrintReverse:
It **prints** the entire table in **reverse**. It takes **no** argumnets.

### length:
It returns the **length** of the table, **i.e** number of key/values pairs stored in the table. It takes **no** argumnets.
