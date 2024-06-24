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
```

