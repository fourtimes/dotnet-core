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

Output: //  he is an not male
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
            }else if(!isMale && isTall)
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



