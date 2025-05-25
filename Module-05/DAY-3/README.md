# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `NA`:
-	a) Private variables `num1` and `num2`
-	b) Method `setsum(int num1, int num2)` to set values of `num1` and `num2`
-	c) Method `getsum()` to calculate and print `sum = num1 + num2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `num1` and `num2`
-	b) Create ` SumCalculator ` object, set values, and call `getsum()`
4.	End

## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: YASHWINI M
RegisterNumber:  212223230249
*/

import java.util.*;
class NA {
    int num1;
    int num2;
    public NA() {
        this.num1 = 0;
        this.num2 = 0;
    }
    public int getNum1() {
        return num1;
    }
    public void setNum1(int num1) {
        this.num1 = num1;
    }
    public int getNum2() {
        return num2;
    }
    public void setNum2(int num2) {
        this.num2 = num2;
    }
    public int calculateSum() {
        return num1 + num2;
    }
}
public class SumCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        NA adder = new NA();
        String input1 = scanner.nextLine();
        try {
            int number1 = Integer.parseInt(input1);
            adder.setNum1(number1);
        } catch (NumberFormatException e) {
            scanner.close();
            return;
        }
        String input2 = scanner.nextLine();
        try {
            int number2 = Integer.parseInt(input2);
            adder.setNum2(number2);
        } catch (NumberFormatException e) {
            scanner.close();
            return; 
        }
        int sum = adder.calculateSum();
        System.out.println("Sum is " + sum);
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6612ec9b-4dcf-4452-a72f-47bf427aa269)

## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.
