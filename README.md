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

### 5.Write a Java program to find the number of days in a month
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner in = new Scanner(System.in);
        String str = in.nextLine();
        switch(str)
        {
            case "January":
                System.out.println("31");
                break;
            case "February":
                System.out.println("28");
                break;
            case "March":
                System.out.println("31");
                break;
            case "April":
                System.out.println("30");
                break;
            case "May":
                System.out.println("31");
                break;
            case "June":
                System.out.println("30");
                break;
            case "July":
                System.out.println("31");
                break;
            case "August":
                System.out.println("31");
                break;
            case "September":
                System.out.println("30");
                break;
            case "October":
                System.out.println("31");
                break;
            case "November":
                System.out.println("30");
                break;
            case "December":
                System.out.println("31");
                break;
        }
    }
}
```
### OUTPUT
![image](https://user-images.githubusercontent.com/94228215/224473363-36a40c63-e32c-4c1a-ab2f-bc84722c3490.png)

### 6. Write a Java program to print the even numbers from 1 to 20
```
public class Main
{
    public static void main(String[] args)
    {
        int i;
        for(i=0;i<=20;i++)
        {
            System.out.print(+i+"\n");
            i+= 1;
        }
    }
}
```
### OUTPUT
![image](https://user-images.githubusercontent.com/94228215/224473443-a115deca-c6e6-4319-8d66-9f612ca2b3bc.png)

### 7.Write a Java program to create a simple calculator
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner num = new Scanner(System.in);
        int num1 = num.nextInt();
        int num2 = num.nextInt();
        int option = num.nextInt();
        switch(option)
        {
            case 1:
                System.out.println("sum:" + (num1 + num2));
                break;
            case 2:
                System.out.println("mul:" + (num1 * num2));
                break;
            case 3:
                System.out.println("sub:" + (num1 - num2));
                break;
            case 4:
                System.out.println("div:" + (num1 / num2));
                break;
            case 5:
                System.out.println("rem:" + (num1 % num2));
                break;
        }
    }

```
### OUTPUT
![image](https://user-images.githubusercontent.com/94228215/224473589-ae0ab7a6-a828-4c92-b86c-37f91c83343c.png)




