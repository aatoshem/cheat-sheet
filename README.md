# cheat-sheet
A cheat sheet compiled while exploring programming languages


- Map
  ```java        
        // Shorter syntax to access key - value of Map
        for(String key: map.keySet()){
            System.out.println("key: " + key + " value: " + map.get(key));
        }

        // Longer syntax to access key - vale of Map
        for(Map.Entry<String, Integer> entry: map.entrySet()){
            String key = entry.getKey();
            Integer val = entry.getValue();
            System.out.println("key: " + key + " value: " + val);
        }
  ```
- Sets
```java
// Create a HashSet of Strings:
Set<String> shapes = new HashSet<String>();

// Add items to a Set:
shapes.add("square");
shapes.add("triangle");
shapes.add("circle"); 

// Remove a value:
shapes.remove("square");

// Check for a value:
System.out.println(shapes.contains("circle")); // Prints: true

// Finding the size of a Set:
System.out.println(shapes.size()); // Prints: 2

// Iterate through a Set:
for (String item: shapes) {
  System.out.println(item);
}
/* Prints:
triangle
circle
*/
```
- Print Even/Odd Numbers (start from 1 (odd) or start from 0 (even))
```java
public class ForLoopExample {
    public static void main(String[] args) {
        // Example: Printing even numbers from 1 to 10
        for (int i = 1, j = 2; i <= 10; i++, j += 2) {
            System.out.println(j);
        }
    }
}
```
