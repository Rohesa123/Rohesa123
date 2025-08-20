
Just Try this code in Java Playgound : 

```java
public class Profile {

    public static void main(String[] args) {

        int[] secretCode = {32,72,105,44,32,73,39,109,32,82,111,104,101,115,97,32,83,105,100,105,113,32,80,101,114,109,97,110,97,10,10,32,73,39,109,32,105,110,116,101,114,101,115,116,101,100,32,105,110,32,80,72,80,44,32,74,97,118,97,44,32,74,97,118,97,83,99,114,105,112,116,44,32,65,110,100,32,68,97,114,116,32,10,10,32,73,39,109,32,99,117,114,114,101,110,116,108,121,32,108,101,97,114,110,105,110,103,32,80,72,80,44,32,74,97,118,97,44,32,80,111,115,116,103,114,101,83,81,76,44,32,77,121,83,81,76,44,32,72,84,77,76,44,32,67,83,83,44,32,74,97,118,97,83,99,114,105,112,116,44,32,65,110,100,32,68,97,114,116,32,10};

        StringBuilder originalOutput = new StringBuilder();
        for (int code : secretCode) {
            originalOutput.append((char) code);
        }

        System.out.print(originalOutput.toString());
        
    }
    
}
```

<!---
Rohesa123/Rohesa123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
