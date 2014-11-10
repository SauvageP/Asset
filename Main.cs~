using System;

namespace Asset
{
	public abstract class Asset
	{
//		public String name;
		public abstract decimal NetValue { get ;}
//		
//		public static void Main (string[] args)
//		{
//			House mansion = new House{name= "McMansion", Mortage= 250000};
//			Asset a = mansion;
//			Console.WriteLine(mansion.Liability);
//			Console.WriteLine(a.Liability);
//		}
	}

	public class Stock : Asset
	{
		public long SharesOwned;
		public decimal currentPrice;
		public override decimal NetValue { 
			get 
			{
				return currentPrice * SharesOwned;
			}
		}
		
	}
//	public class House : Asset 
//	{
//		public decimal Mortage;
//		public override decimal Liability { get {return Mortage;}}
//	}
}
