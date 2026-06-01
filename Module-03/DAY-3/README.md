# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder

## ALGORITHM :
1.  Start the Program
2.	Import `Scanner` and define class `replace`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a string `str` from user input
4.	Create a `StringBuilder` object `sb` initialized with `str`
5.	Use the `replace()` method to replace characters from index 1 to 3 with "Java"
6.	Print the modified string using `sb.toString()`
7.	End






## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: Harini.S
RegisterNumber:  212223040058
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

public class StringBuilderAppend {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String input = scanner.nextLine();
        scanner.close();

        StringBuilder sb1 = new StringBuilder(input); // Initialize with input
        sb1.append("s");

        System.out.println("sb1 = " + sb1.toString());
    }
}
```

## OUTPUT:

<img width="791" height="266" alt="image" src="https://github.com/user-attachments/assets/5ef5d9c4-ece5-44c8-831a-6d031e6adf3d" />


## RESULT:
Thus the java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder was executed successfully.



