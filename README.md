# Reverse-String
Reversing a String
using System;

namespace ReverseString
{
    class RString
    {
        static void Main(string[] args)
        {
            string str, rev;
            str = "programming";
            rev = " ";

            Console.WriteLine("Value of the given string is: {0}", str);

            //find string length
            int a;
            a = str.Length - 1;
            while (a >= 0)
            {
                rev = rev + str[a]; //rev + str[str.length-1]
                a --;
            }
            Console.WriteLine("Reverse String is: {0}", rev);
            Console.ReadLine();
        }
    }
}
