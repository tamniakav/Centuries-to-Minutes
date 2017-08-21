# Centuries-to-Minutes
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Centuries_to_Minutes
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Centuries = ");
            int centuties = int.Parse(Console.ReadLine());
            int years = centuties * 100;
            double days = years * 365.2422;
            int hours =(int) days * 24;
            int minutes = hours * 60;

            Console.WriteLine($"{centuties} centuries = {years} years = {Math.Round(days)} days = {hours} hours = {minutes} minutes");
        }
    }
}
