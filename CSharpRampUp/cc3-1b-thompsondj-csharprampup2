//Part 1
using System;
using System.Data;
namespace CSharpRampUp
{
    public class Progra
    {
        public static void Main(string[] args)
        {
            //CONVERT POUNDS to KILOGRAMS

            Console.WriteLine("Weight in Pounds (lbs):");
            double pounds = 0;
            bool invalidInput = false;

            do
            {
                if (!double.TryParse(Console.ReadLine(), out pounds) || pounds < 0)
                {

                    invalidInput = true;
                }
            } while (pounds < 0 && !invalidInput);

            if (invalidInput)
            {
                Console.WriteLine(" invalid input.");
                return;
            }

            double kilograms = pounds * 0.45359237;
            Console.WriteLine($"Weight Converted to Kilograms: {kilograms}");
            Console.WriteLine("=========================");

            //CONVERT MILES TO KILOMETERS
            Console.WriteLine("Length in Miles(mi):");
            double miles = Convert.ToDouble(Console.ReadLine());
            while (miles < 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            double kilometers = miles * 1.6;
            Console.WriteLine($"Length in Kilometers (km):{kilometers}");
            Console.WriteLine("=========================");
            //CONVERT FAHRENHEIT TO CELSIUS

            Console.Write("Temperature in Fahrenheit (F):");
            double fahrenheit = Convert.ToDouble(Console.ReadLine());
            while (fahrenheit < 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            double celsius = fahrenheit - 32 * .5556;
            Console.WriteLine($"Temperature in Celscius(C):{celsius}");
            Console.WriteLine("=========================");
            //AVERAGE AGE OF STUDENTS
            Console.WriteLine("Age of Student 1:");
            double age1 = Convert.ToDouble(Console.ReadLine());
            while (age1 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }

            Console.WriteLine("Age of Student 2:");
            double age2 = Convert.ToDouble(Console.ReadLine());
            while (age2 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            Console.WriteLine("Age of Student 3:");
            double age3 = Convert.ToDouble(Console.ReadLine());
            while (age3 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            Console.WriteLine("Age of Student 4:");
            double age4 = Convert.ToDouble(Console.ReadLine());
            while (age4 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            Console.WriteLine("Age of Student 5:");
            double age5 = Convert.ToDouble(Console.ReadLine());
            while (age5 <= 0)
            {
                Console.WriteLine("InvalidInput");
                break;
            }
            Console.WriteLine("Age of Student 6:");
            double age6 = Convert.ToDouble(Console.ReadLine());
            while (age6 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            Console.WriteLine("Age of Student 7:");
            double age7 = Convert.ToDouble(Console.ReadLine());
            while (age7 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            Console.WriteLine("Age of Student 8:");
            double age8 = Convert.ToDouble(Console.ReadLine());
            while (age8 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            Console.WriteLine("Age of Student 9:");
            double age9 = Convert.ToDouble(Console.ReadLine());
            while (age9 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            Console.WriteLine("Age of student 10:");
            double age10 = Convert.ToDouble(Console.ReadLine());
            while (age10 <= 0)
            {
                Console.WriteLine("Invalid Input");
                break;
            }
            Console.WriteLine($"The average of students is {age1 + age2 + age3 + age4 + age5 + age6 + age7 + age8 + age9 + age10 / 10}");
            Console.WriteLine("========================================");
            //FANTASY STORY
            //Characters
            string evil = "Satan";
            string evil2 = "Belial";
            string evil3 = "Lucifer";
            string good = "Zeus";
            string good2 = "Posiedon";
            //ITEM NAMES/ABILITY NAMES
            string ability1 = "Lightning Strike";
            string item = "Demon Waker";
            string power = "Doom Death";
            string ability2 = "Black Hole";
            string ability3 = "Meteorshower";
            //fantasy story
            string fantasystory = $@"Once upon a time,In the Universe of God's and Evil,where magic and gods exist.In a Planet called Cancrie .There Lived an Evil God named <{evil}> 
and his two brothers named <{evil2}> and <{evil3}>.They ruled the universe causing havoc and death to any living thing's they see,destroying planets and massacring living being's.
Nobody can stop them...but one day.Two Gods's appeared out of nowhere named <{good}> and <{good2}>.The two mysterious God's faught against the Evil brother's.<{good}> used his <{ability1}> power's to cause large thunderstorms.
{good2}Used his {power} power's to cause massive earthquake and typhoon.{evil2} used his staff {item} to summon thousand's of demons.<{good}> used his ability <{ability3}> to summon meteor's and  to eleminate the demon's.
The two God's managed to defeat <{evil2}> and <{evil3}>.<{evil}> was furious so he used his ultimate ability <{ability2}>.He summoned a massive massive black hole.
The black hole devoured everything until nothing existed except the dark black hole itself.";
            Console.WriteLine(fantasystory);
            //Part 2
            Console.WriteLine("Enter a digit:");
            if (int.TryParse(Console.ReadLine(), out int input) && input > 0)
            {
                for (int i = 1; i <= input; i++)
                {
                    for (int j = 1; j <= i; j++)
                    {
                        Console.Write(j);
                    }
                    Console.WriteLine();
                }
            }
            else
            {
                Console.WriteLine("Invalid Input. ");
            }
            Console.WriteLine("Enter a number:");
            if (int.TryParse(Console.ReadLine(), out input) && input >= 1)
            {
                int sum = 0;

                // Calculate the sum of integers 
                for (int i = 1; i <= input; i++)
                {
                    sum += i;
                }

                Console.WriteLine($"The sum of integers from 1 to {input} is: {sum}");
            }
            else
            {
                Console.WriteLine("Invalid Input.");
            }

            Console.WriteLine("Enter a digit:");
            if (int.TryParse(Console.ReadLine(), out input) && input > 0)
            {
                for (int i = input; i >= 1; i--)
                {
                    for (int j = 1; j <= i; j++)
                    {
                        Console.Write(j + " ");
                    }
                    Console.WriteLine();
                }
            }
            else
            {
                Console.WriteLine("Invalid Input.");
            }

        }
    }

}

