|        | XL Array    | L Array     | M Array     | S array     | Tiny Array  |
|--------|-------------|-------------|-------------|-------------|-------------|
| insert | 822.17215 ms| 967.430 ms  | 196.4 μs    | 43.1 μs     | 30.8 μs     |
| append | 2.826492 ms | 453.98 μs   | 143 μs      | 197.5 μs    | 135.5 μs    |
|        |             |             |             |             |             |



In general, it looks like the appended () is working a bit better. You can notice as the array increases for both, the time also increases, however the interested function exponentially increases.  I think the doublerInsert () has a time complexity of 0(n) with a linear growth, and doublerAppened() time complexity of 0(n2). 