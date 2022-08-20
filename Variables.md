# variables-in-c-sharp
 www.patika.dev

using System;
using System.IO;

namespace degiskenler;
class program {
	
	// Main Method
	public static void Main(string[] args)

	{
		Console.WriteLine("");

		byte b = 5; 	// 1 byte
		sbyte c = 3; 	// 1 byte

		short s = 5; 	//2 byte
		ushort us=5;

		Int16 i16=2; 	//2 byte
		int i=2;     	//4 byte
		Int32 i32=2; 	//4 byte

		uint ui=2;  	//4 byte
		long l=4;  		//8 byte

		float f=5; 		//4 byte
		double d=5; 	//8 byte
		decimal de=5; 	//16 byte

		char ch='2'; 		//2 byte
		string str="Orkun";	//sınırsız

		bool b1=true; 
		bool b2=false;

		DateTime dt =DateTime.Now;

		Console.WriteLine(dt);

		object o1 = "x";
		object o2 = 'y';
		object o3 = 4;
		object o4 = 4.3;

		// String ifadeleri

		string str1= string.Empty;
		str1="Orkun Koçak";
		string ad ="Orkun";
		string soyad="Koçak";
		string TamIsim= ad + " " + soyad;

		//integer tanımlama 

		int integer1= 5;
		int integer2= 3;
		int integer3= integer1 * integer2;

		//boolean

		bool bool1= 10<2; //false
		bool boll2= 2>10;  //true

		//Değişken Dönüşümleri

		string str20 = "20";
		int int20 = 20;
		string yenideger = str20 + int20.ToString();
		Console.WriteLine(yenideger); //2020

		int int21 = int20 + Convert.ToInt32(str20);
		Console.WriteLine(int21); //40
		
		int int22= int20 + int.Parse(str20); //40 --> Stringten dönüşüm için 
		
		// Datetime
		string datetime= DateTime.Now.ToString("dd.MM.yyyy"); 
		Console.WriteLine(datetime);

		string datetime2= DateTime.Now.ToString("dd/MM/yyyy"); 
		Console.WriteLine(datetime2);
		
		string hour= DateTime.Now.ToString("HH:mm"); 
		Console.WriteLine(hour);
	}
}
**
