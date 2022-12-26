
Just Try this code in Java Playgound : 

```java
public class Profile {

    public static void main(String[] args) {
    
        String name = "Rohesa Sidiq Permana";
        String[] interestedIn = {"PHP","Java","JavaScript"};
        String[] learning = {"PHP","Java","PostgreSQL","MySQL","HTML","CSS","JavaScript"};
        
        System.out.println(" Hi, I'm " + name + "\n");
        
        System.out.print(" I'm interested in ");

        for (int i = 0; i < interestedIn.length; i++) {
            if ( i < (interestedIn.length - 1)) System.out.print(interestedIn[i]+", ");
            if ( i == (interestedIn.length - 1)) System.out.print("And "+interestedIn[i]+" \n");
        }

        System.out.print("\n I'm currently learning ");

        for (int i = 0; i < learning.length; i++) {
            if ( i < (learning.length - 1)) System.out.print(learning[i]+", ");
            if ( i == (learning.length - 1)) System.out.print("And "+learning[i]+" \n");
        }
        
    }
    
}
```

<!---
Rohesa123/Rohesa123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
