# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To implement a Java program to associate the specified value with the specified key in a Tree Map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
7.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: Yashwini M
RegisterNumber: 212223230249

import java.util.*;
public class demo{
    public static void main(String args[]){
        TreeMap<Integer,String> tee = new TreeMap<Integer,String>();
        Scanner sc = new Scanner(System.in);
        int s = sc.nextInt();
        for(int i=0;i<s;i++){
            Integer a = sc.nextInt();
            String b = sc.next();
            tee.put(a,b);
        }
        for(Map.Entry<Integer,String> t:tee.entrySet())
        {
            System.out.println(t.getKey() + "=>"+t.getValue());
        }
    }
}
*/
```

## Sourcecode.java:







## OUTPUT:
![Uploading image.png…]()



## RESULT:
Thus the Java program to associate the specified value with the specified key in a Tree Map was executed successfully.
