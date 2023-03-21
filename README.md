# Pattern

## Aim:
To write a C# program for a pascal's triangle
## Equipment Required:
C# Compiler or visual studio


## Algorithm:
### Step 1:
Initialize the necessary attributes.

### Step 2:
Get the limit from the user.

### Step 3:
using for loop print the rows and columns and space.

### Step 4:
Check the first and last rows of the triange is 1 using if condition.

### Step 5:
Otherwise use else to print the inner value

val = val * (i - j + 1) / j;

### Step 6:
Check the program for any error.

if not.

### Step 7:
print the program.

## Program:
~~~
using System;
namespace Pascal
{
    public class program
    {
        static void Main(string[] args)
        {
            int rows,i,val=1;
            Console.WriteLine("Enter the number: ");
            rows = Convert.ToInt32(Console.ReadLine());
            for(i=0;i<rows;i++)
            {
                for (int space = 1; space < rows - i; space++)
                {
                    Console.Write(" ");
                }
                    for(int j=0;j<=i;j++)
                    {
                        if (i == 0 || j == 0)
                        {
                            val = 1;
                        }
                        else
                        {
                            val = val * (i - j + 1) / j;
                        }
                    Console.Write(val + " ");
                }
                Console.WriteLine();
            }
        }

    }
}
~~~

## Output:
![output]()

## Result:
Thus,To write a C# program for a pascal's triangle is written and executed.


