# C-sharp
 www.patika.dev
 
using System;

namespace operatorler
{
    class Program
    {
        static void Main(string[] args)
        {
            //Atama ve İşlemli Atama
            Console.WriteLine("******Atama ve atama operatorleri*********");

            int x = 3;
            int y = 3;
            y= y+2;
            Console.WriteLine(y);   //outout:2
            y += 2;
            Console.WriteLine(y);   // "    :5
            y /= 1;
            Console.WriteLine(y);   // "    :7
            x *=2;
            Console.WriteLine(x);   // "     :6
                             
            Console.WriteLine("******Mantıksal Operatörler*********");    

            //Mantıksal Operatorler
            // || , && , !

            bool isSuccess = true;
            bool isCompleted = false;

            if(isSuccess && isCompleted)
            {
                Console.WriteLine("helal");
            }
            if(isSuccess || isCompleted)
            {
                Console.WriteLine("müko");
            }
            if(isSuccess && ! isCompleted)
            {
                Console.WriteLine("iyi");
            }

            Console.WriteLine("******İlişkisel Operatörler*********");
            //İliskisel Operatorler
            //>,<,>=,<=,==,!=

            int a = 3;
            int b = 4;
            bool sonuc = b>a; //True

            Console.WriteLine(sonuc);
            sonuc = a>b;
            Console.WriteLine(sonuc);//False
            sonuc= a>=b;
            Console.WriteLine(sonuc);//False
            sonuc=a<=b;
            Console.WriteLine(sonuc);//True
            sonuc= a==b;
            Console.WriteLine(sonuc);//False
            sonuc= a!=b;
            Console.WriteLine(sonuc);//True
            
            Console.WriteLine("******Aritmatik Operatörler*********");
            //Aritmatik Operatorler
            //      / , * , -, +

            int sayi1=10;
            int sayi2=5;
            int sonuc1=sayi1/sayi2;
            Console.WriteLine(sonuc1);
            sonuc1= sayi1 * sayi2;
            Console.WriteLine(sonuc1);
            sonuc1=sayi1+sayi2;
            Console.WriteLine(sonuc1);
            sonuc1 =sayi1++;
            Console.WriteLine(sonuc1);
            
            // % mod almak için
            int sonuc2= 20%3;
            Console.WriteLine(sonuc2);
        }
    }             
    
}
