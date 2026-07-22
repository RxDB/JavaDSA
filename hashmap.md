## HashSet
```java
HashSet<Integer> set = new HashSet<>();

set.add(10);        // insert
set.remove(10);     // delete
set.contains(10);   // search
set.size();         // number of elements
set.isEmpty();      // check empty
set.clear();        // remove all elements
```

## HashMap
```java
HashMap<Integer, Integer> map = new HashMap<>();

map.put(key, value);                  // insert or update
map.get(key);                         // get value
map.getOrDefault(key, defaultValue);  // get value with default
map.containsKey(key);                 // check key
map.containsValue(value);             // check value
map.remove(key);                      // delete by key
map.remove(key, value);               // delete exact key-value pair
map.size();                           // number of entries
map.isEmpty();                        // check empty
map.clear();                          // remove all entries
```

```java
for (Map.Entry<Integer, Integer> entry : map.entrySet()) {
    int key = entry.getKey();
    int value = entry.getValue();
}
```

Key points:
- Both are unordered.
- Average `O(1)` for insert, delete, and search.
