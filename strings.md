## String
```java
s.length();                     // number of characters
s.charAt(index);                // get character
s.substring(start, end);        // get substring [start, end)
s.contains(str);                // check substring
s.indexOf(str);                 // first index of substring
s.lastIndexOf(str);             // last index of substring
s.equals(other);                // compare content
s.equalsIgnoreCase(other);      // compare content ignoring case
s.compareTo(other);             // lexicographic compare
s.toLowerCase();                // convert to lowercase
s.toUpperCase();                // convert to uppercase
s.trim();                       // remove leading and trailing spaces
s.replace(oldChar, newChar);    // replace characters
s.split(regex);                 // split into array
s.toCharArray();                // convert to char array
```
```java
String s = new String(arr);     // char array to string
String s = String.valueOf(num); // int to string
int num = Integer.parseInt(s);  // string to int
```
## StringBuilder
```java
StringBuilder sb = new StringBuilder();
StringBuilder sb = new StringBuilder(s);

sb.append(value);               // add at end
sb.insert(index, value);        // insert at index
sb.delete(start, end);          // delete range [start, end)
sb.deleteCharAt(index);         // delete character
sb.setCharAt(index, ch);        // update character
sb.charAt(index);               // get character
sb.length();                    // number of characters
sb.reverse();                   // reverse characters
sb.toString();                  // convert to string
sb.setLength(0);                // clear
```

Key points:
- `String` is immutable.
- `StringBuilder` is mutable.
