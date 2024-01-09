# cheat-sheet
A cheat sheet compiled while exploring programming languages


- Accessing key-value in Map
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

```)
