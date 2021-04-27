using System;
					
public class Product
{
	public void invoice()
	{
		Console.WriteLine("Enter the total no. of quantity");
		int n = Convert.ToInt32(Console.ReadLine());
		for(int i=1;i<=n;i++)
		{	
			Console.Write("\n Enter the Product name:");
			string name =Console.ReadLine();
			Console.WriteLine("Enter the Product quantity:");
			int pquan = Convert.ToInt32(Console.ReadLine());
			Console.WriteLine("Enter the Product price for one:");
			int pprice = Convert.ToInt32(Console.ReadLine());
			Console.Write("S.No:  " );
			Console.Write("Product Name:  " );
			Console.Write("Product quantity:  " );
			Console.Write("Product price:  " );
			Console.WriteLine("Total price:  ");
			Console.Write(i+"  ");
			Console.Write(name+"  ");
			Console.Write(pquan+"  ");
			Console.Write(pprice+"  ");
			Console.Write(pprice*pquan+"  ");
		}
	}
	public void Main()
	{
		Product prod=new Product();
		prod.invoice();
		Console.ReadLine();
	}
}