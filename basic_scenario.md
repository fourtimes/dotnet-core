**_Method with Arguments_**
```cs
using System;

namespace demo
{
    class Program 
    {
        static void Main()
        {
            SayHi("Ashli", 40);
        }
        
        // using Method with Arguments
        static void SayHi(string name, int age)
        {
            Console.WriteLine("Say Hi " + name + ". Her age is " + age);
        }
    }
}

Output: // Say Hi Ashli. Her age is 40
```
**_Method with arguments with return statement_**
```cs
using System;

namespace demo
{
    class Program 
    {
        static void Main()
        {
            Console.WriteLine(square(5));
        }

        // method with datatype and argument 
        static int square(int num)
        {
            int result = (num * num);
            return result;
        }

    }
}

Output: //  25
```

**_If else statement_**
```cs
using System;  // .net framework

namespace demo
{
    class Program 
    {
        static void Main()
        {
            bool isMale = true;

            if (isMale)
            {
                Console.WriteLine( "he is an male");
            }
            else
            {
                Console.WriteLine( "he is an not male");
            }
        } 
    }
}

Output: //  he is an male
```
**_If elseif statement_**
```cs
using System;

namespace demo
{
    class Program 
    {
        static void Main()
        {
            bool isMale = false;
            bool isTall = false;

            if (isMale && isTall)
            {
                Console.WriteLine("He is a tall male.");
            } 
            else if (isMale && !isTall)
            {
                Console.WriteLine("He is a male. but not tall.");
            }
            else if(!isMale && isTall)
            {
                Console.WriteLine("You are not male. but you are tall.");
            }
            else
            {
                Console.WriteLine("You are not male and tall.");
            }
        }

    }
}
Output: //  You are not male and tall.
```
```cs
using System;

namespace demo
{
    class Program 
    {
        static void Main()
        {
            Console.Write("Enter your first number: ");
            double num1 = Convert.ToDouble(Console.ReadLine());

            Console.Write("Enter your Operator: ");
            string op = Console.ReadLine();

            Console.Write("Enter your another number: ");
            double num2 = Convert.ToDouble(Console.ReadLine());

            if ( op == "+" )
            {
                Console.WriteLine(num1 + num2);
            }else if (op == "-")
            {
                Console.WriteLine(num1 - num2);
            }else if (op == "*")
            {
                Console.WriteLine(num1 * num2);
            }else if (op == "/")
            {
                Console.WriteLine(num1 / num2);
            }else {
                Console.WriteLine ("some input values not correct");
            }
        }
    }
}
```
**_Function method with if else condition_**
```cs
using System;

namespace demo
{
    class Program 
    {
        static void Main()
        {
            Console.WriteLine(GetMax(10000,10001));
        }

        static int GetMax(int num1, int num2)
        {
            int result;
            if (num1 > num2)
            {
                result = num1;
            }
            else
            {
                result = num2;
            }
            return result;
        }

    }
}

Output: // 10001
```

**_Switch statement_**
```cs
using System;

namespace demo
{
    class Program 
    {
        static void Main()
        {
            Console.WriteLine(GetDay(5));
        }

        static string GetDay(int dayNum) 
        {
            string dayName;
                
            switch (dayNum)
            {
                case 0:
                    dayName = "Sunday";
                    break;
                case 1:
                    dayName = "Monday";
                    break;
                case 2:
                    dayName = "Tuesday";
                    break;
                case 3:
                    dayName = "Wednesday";
                    break;
                case 4:
                    dayName = "Thursday";
                    break;
                case 5:
                    dayName = "Friday";
                    break;
                case 6:
                    dayName = "Saturday";
                    break;              
                default:
                    dayName = "unknown day";
                    break;
            }
            return dayName;
        }
    }
}
```
