## Vectors

### Iterators

|   function    |                     Definition                     |
|---------------|----------------------------------------------------|
|     begin     | Return iterator to beginning                       |
|      end      | Return iterator to end                             |
|    rbegin     | Return reverse iterator to reverse beginning       |
|     rend      | Return reverse iterator to reverse end             |
|    cbegin     | Return const_iterator to beginning                 |
|     cend      | Return const_iterator to end                       |
|  crbegin      | Return const_reverse_iterator to reverse beginning |
|    crend      | Return const_reverse_iterator to reverse end       | 


### Capacity

|   function    |                  Definition               |
|---------------|-------------------------------------------|
|      size     | Return size                               |
|  max_size     | Return maximum size                       |
|    resize     | Change size                               |
|  capacity     | Return size of allocated storage capacity |
|     empty     | Test whether vector is empty              |
|   reserve     | Request a change in capacity              |
| shrink_to_fit | Shrink to fit                             |


### Element access

|   function    |          Definition           |
|---------------|-------------------------------|
|      []       | Access element [<pos>]        |
|      at       | Access element at(<pos>)      |
|    front      | Access first element          |
|     back      | Access last element           |
|     data      | Access data                   | 


### Modifiers

|   function    |               Definition                |
|---------------|-----------------------------------------|
|    assign     | Assign vector content                   |
|  push_back    | Add element at the end                  |
|   pop_back    | Delete last element                     |
|    insert     | Insert elements                         |
|     erase     | Erase elements                          |
|     swap      | Swap content                            |
|     clear     | Clear content                           |
|   emplace     | Construct and insert element            |
| emplace_back  | Construct and insert element at the end | 

