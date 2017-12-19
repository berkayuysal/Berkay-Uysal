# Berkay-Uysal
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("kelimegirin:");
            string s = Console.ReadLine();

            Console.Write("ASCII kodu:");
            foreach (char c in s)
            {
                Console.Write(System.Convert.ToInt32(c) + "");

            }
            Console.WriteLine();
            Console.Write("ASCII +10 :");
            foreach(char c in s)
            {
                Console.Write(System.Convert.ToInt32(c + 10) + "");
            }
            Console.WriteLine();
            Console.Write("yeni kelime:");
            foreach(char c in s)
            {
                Console.Write(System.Convert.ToChar(c + 10));
            }
            Console.ReadKey();
        }
    }
}
