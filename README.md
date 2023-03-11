# Assignment-1
### 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner num = new Scanner(System.in);
        int num1 = num.nextInt();
        int num2 = num.nextInt();
        System.out.println("sum:"+(num1+num2));
        System.out.println("mul:"+(num1*num2));
        System.out.println("sub:"+(num1-num2));
        System.out.println("div:"+(num1/num2));
        System.out.println("rem:"+(num1%num2));
    }
}
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/94228215/224472883-92b411df-7227-43ee-a0da-a49a14c7824e.png)

### 2. Write a Java program to compare two numbers
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner num = new Scanner(System.in);
        int num1 = num.nextInt();
        int num2 = num.nextInt();
        if(num1 > num2)
        {
            System.out.println(num1 + " is greater than " + num2);
        }
        else if(num1 < num2)
        {
            System.out.println(num1 + " is less than " + num2);
        }
        else
        {
            System.out.println(num1 + " is equal to " + num2);
        }

    }
}
```
### OUTPUT
![image](https://user-images.githubusercontent.com/94228215/224472982-4a0acab4-9f02-442f-98ef-b35dd1d57c76.png)

### 3. Write a Java program to convert a string to an integer
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner in = new Scanner(System.in);
        System.out.printf("Enter a string:");
        String str = in.nextLine();
        int res = Integer.parseInt(str);
        System.out.printf("Integer value:%d",res);
        System.out.printf("\n");
    }
}
```
### OUTPUT
![image](https://user-images.githubusercontent.com/94228215/224473107-a9c7cd8c-d7f3-4eb8-9911-9f690a56f40f.png)

### 4. Java Program to find area of rhombus
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner in = new Scanner(System.in);
        int num1 = in.nextInt();
        int num2 = in.nextInt();
        System.out.println("Area of rhombus:"+((num1*num2)/2));
    }
}
```
### OUTPUT
![image](https://user-images.githubusercontent.com/94228215/224473175-2d4d844a-1474-4052-86f6-8264f481ce61.png)


