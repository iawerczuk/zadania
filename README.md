//Pierwszy program - rozgrzewka

////zadanie 1
//using System;
//namespace zad1
//{
//    class Program
//    {
//        static void Main(string[] args)
//        {
//            Console.WriteLine("Podaj imię:");
//            var name = Console.ReadLine();
//            Console.WriteLine("Witaj " + name + "!");
//            Console.ReadLine();

//        }
//    }
//}



////zadanie 2
//using System;
//namespace zad2
//{
//    class Program
//    {
//        static void Main(string[] args)
//        {
//            int result = 5 + 9;
//            Console.WriteLine("Wynik= " + result);
//            Console.ReadLine();
//        }
//    }
//}

////zadanie 3 
//using System;
//using System.Collections.Generic;
//using System.Linq;
//using System.Text;
//using System.Threading.Tasks;

//namespace zad3
//{
//    class Program
//    {
//        static void Main(string[] args)
//        {
//            int number = 1;                            
//            float money = 11.11f;                      
//            string text = "Cześć :)";              
//            bool isLogged = true;                       
//            char myChar = 'A';                          
//            decimal price = 25000m;       

//            Console.WriteLine("number: " + number);
//            Console.WriteLine("money: " + money);
//            Console.WriteLine("text: " + text);
//            Console.WriteLine("isLogged: " + isLogged);
//            Console.WriteLine("myChar: " + myChar);
//            Console.WriteLine("price: " + price);
//            Console.ReadLine(); 
//        }
//    }
//}

////zadanie 4.
//using System;

//class Zad4
//{
//    static void Main()
//    {
//        int a = 5;
//        int b = 12;

//        int add = a + b;
//        int sub = a - b;
//        int mul = a * b;
//        int mod = a % b;

//        int div = a / b;

//        Console.WriteLine("Dodawanie: " + add);
//        Console.WriteLine("Odejmowanie: " + sub);
//        Console.WriteLine("Mnożenie: " + mul);
//        Console.WriteLine("Dzielenie: " + div);
//        Console.WriteLine("Modulo: " + mod);
//        Console.ReadLine(); 

//    }
//}

//zadanie 5
//using System;

//class zad5
//{
//    static void Main(string[] args)
//    {
//        string a = "Ala ";
//        string b = "ma ";
//        string c = "kota.";

//        string result = a + b + c;

//        Console.WriteLine(result);
//        Console.ReadLine(); 

//    }
//}
//Instrukcje sterujące i pętle
//zadanie 1


//using System;

//class Program
//{
//    static void Zad1()
//    {
//        int n1 = 10;
//        int n2 = 20;

//        if (n1 > n2)
//        {
//            Console.WriteLine(n1 + " jest większe od " + n2);
//        }
//        else if (n1 < n2)
//        {
//            Console.WriteLine(n1 + " jest mniejsze od " + n2);
//        }
//        else
//        {
//            Console.WriteLine(n1 + " jest równe " + n2);
//        }
//Console.ReadLine(); 
//    }
//}

//zadanie 2

//using System;

//class zad2
//{
//    static void Main()
//    {
//        for (int i = 0; i < 10; i++)
//        {
//            Console.WriteLine("C#");
//        }

//        int count = 0;

//        while (count < 10)
//        {
//            Console.WriteLine("C#");
//            count++;
//        }
//        Console.ReadLine(); 
//    }
//}



//zadanie 3

//using System;

//class zad3
//{
//    static void Main()
//    {
//        int n = 10;

//        for (int i = 0; i <= n; i++)
//        {
//            if (i % 2 == 0)
//            {
//                Console.WriteLine(i + " - Parzysta");
//            }
//            else
//            {
//                Console.WriteLine(i + " - Nieparzysta");
//            }
//        }
//     Console.ReadLine(); 

//    }
//}


//zadanie 4

//using System;

//class zad4
//{
//    static void Main()
//    {
//        int n = 5;

//        for (int i = 1; i <= n; i++)
//        {
//            for (int j = 1; j <= i; j++)
//            {
//                Console.Write("* ");
//            }
//            Console.WriteLine();
//        }

//    }
//}


//zadanie 5
//using System;

//class zad5
//{
//    static void Main()
//    {
//        int exam = 57;

//        switch (exam)
//        {
//            case int n when (n < 0 || n > 100):
//                Console.WriteLine("Wartość poza zakresem.");
//                break;
//            case int n when (n <= 39):
//                Console.WriteLine("Ocena niedostateczna");
//                break;
//            case int n when (n <= 54):
//                Console.WriteLine("Ocena dopuszczająca");
//                break;
//            case int n when (n <= 69):
//                Console.WriteLine("Ocena dostateczna");
//                break;
//            case int n when (n <= 84):
//                Console.WriteLine("Ocena dobra");
//                break;
//            case int n when (n <= 98):
//                Console.WriteLine("Ocena bardzo dobra");
//                break;
//            case int n when (n <= 100):
//                Console.WriteLine("Ocena celująca");
//                break;
//        }
//        Console.ReadLine();
//    }
//}
//kolekcje
//zadanie 1 

//using System;

//class zad1
//{
//    static void Main()
//    {
//        string[] colors = { "blue", "navy", "black", "white" };

//        Console.WriteLine("Mój pierwszy kolor to: " + colors[0]);

//        Console.WriteLine("Mój ostatni kolor to: " + colors[colors.Length - 1]);

//        Console.ReadLine();
//    }
//}

//zadanie 2

//using System;

//class zad2
//{
//    static void Main()
//    {
//        int[] numbers = { 10, 1, 19, 87, 19, 5, 20, 24, 26, 37 };

//        Console.WriteLine("Pętla for:");
//        for (int i = 0; i < numbers.Length; i++)
//        {
//            Console.WriteLine("Liczba: " + numbers[i]);
//        }

//        Console.WriteLine("\nPętla foreach:");
//        foreach (int number in numbers)
//        {
//            Console.WriteLine("Liczba: " + number);
//        }

//        Console.WriteLine("\nPętla while:");
//        int index = 0;
//        while (index < numbers.Length)
//        {
//            Console.WriteLine("Liczba: " + numbers[index]);
//            index++;
//        }
//        Console.ReadLine();
//    }
//}


//zadanie 3
using System;
using System.Collections.Generic;

class zad3
{
    static void Main()
    {
        List<string> fruits = new List<string> { "strawberry", "mango", "sweetie", "apple" };

        Console.WriteLine(string.Join(", ", fruits));

        fruits.Remove(fruits[0]);

        fruits.RemoveAt(fruits.Count - 1);

        Console.WriteLine(string.Join(", ", fruits));

        Console.ReadLine();
    }
}
