# Arrays
using System;

namespace Arrays
{
    class Program
    {
        static void Main(string[] args)
        {

            string[] wochentage = new string[7]
                { "Sonntag", "Montag", "Dienstag", "Mittwoch", "Donnerstag", "Freitag", "Samstag" };

            int i = 0;
            foreach (string wt in wochentage)
            {
                Console.WriteLine("index: {0}, wochentag: {1}", i, wt);
                i++;
            }


            int j = 0;
            foreach (string wt in wochentage)
            {
                Console.WriteLine("index: {0}, wochentag: {1}", j, wt);
                j = j + 2;

            }

            Console.WriteLine();
        }
    }
}
