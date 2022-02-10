using System;
public class funcexer3
{
    public static int sum(int num1,int num2){
        int total;
        total=num1*num2;
        return total;

    }
    public static void Main(){
        Console.WriteLine("function to calculate the sum of two number");
        Console.WriteLine("/-----------------------");
        Console.WriteLine("enter the number");
        int n1=Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("enter the number");
        int n2=Convert.ToInt32(Console.ReadLine());
        Console.Write("the sum of two number is : {0}",sum(n1,n2));
    }
}
