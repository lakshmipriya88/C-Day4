using System.IO;
using System;

class Program
{
    public void Main()
    {
        int x =1;
        int y;
        try 
        {
            y = x/0;
            Console.Write(y);
            
        }
        catch 
        {
            Console.WriteLine("some error");
        }
        Console.ReadLine();
    }
}