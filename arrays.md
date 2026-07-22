
## Arrays
```java
import java.util.Arrays;

Arrays.toString(arr);                  // print 1D array
Arrays.deepToString(arr);              // print 2D or nested array
Arrays.sort(arr);                      // sort ascending in place
Arrays.fill(arr, value);               // fill with value
Arrays.copyOf(arr, length);            // copy with new length
Arrays.copyOfRange(arr, start, end);   // copy range [start, end)
Arrays.equals(a, b);                   // compare 1D arrays
Arrays.deepEquals(a, b);               // compare nested arrays
Arrays.binarySearch(arr, key);         // search sorted array
Arrays.asList(arr);                    // object array to list
```

## ArrayList
```java
import java.util.ArrayList;
import java.util.Collections;

ArrayList<Integer> list = new ArrayList<>();

list.add(value);                         // add at end
list.add(index, value);                  // add at index
list.get(index);                         // access
list.set(index, value);                  // update
list.remove(index);                      // remove by index
list.remove(Integer.valueOf(value));     // remove by value
list.size();                             // number of elements
list.isEmpty();                          // check empty
list.contains(value);                    // search
list.indexOf(value);                     // first index of value
list.clear();                            // remove all elements
Collections.sort(list);                  // sort ascending
Collections.reverse(list);               // reverse order
list.toArray();                          // convert to array
```

Key points:
- Array size is fixed.
- `ArrayList` size is dynamic.
- `Arrays.sort(arr)` modifies `arr` and returns `void`.
- `Arrays.binarySearch` requires a sorted array.


## 2D Array
```java
int[][] grid = new int[rows][cols];

grid[i][j];         // access
grid[i][j] = value; // update
grid.length;        // number of rows
grid[0].length;     // number of columns
```

```java
for (int i = 0; i < grid.length; i++) {
    for (int j = 0; j < grid[i].length; j++) {
        int value = grid[i][j];
    }
}
```