# HW-WhileLoops
Watch read and practice from the module: Switch Statements, While Loops  Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas.

*The first four examples are from the book.*

"C# enables a sequence of statements to execute repeatedly with the while, do-while, for, and foreach statements."

1) While loops repeat the code's body over and over, until the bool's expression becomes false. And the expression gets tested before a/the loops execution.

int i = 0;
while (i < 3)
{
  Console.Writeline (i++);
}

RESULT: i == 0, 1, & 2.

2) Do-While Loops are the same thing as the regular while loops, except the bool expression is tested after the execution.

int i = 0;
do
{
  Console.Writeline(i++);
}
while (i < 3);

RESULT: i == 1 & 2

3) Similar to while loops, for loops have special clauses for a loop variable's initialization and iteration.

for (int i = 0; i < 3; i++)
  Console.Writeline (i);

4) Iterating the code's elements (in an enumerable object) are known as foreach loops.

foreach (char c in "beer")
  Console.Writeline (c + "beer");

5) This shows that we start with the number 10, and that 10 is less than 20. After the execution, it is given an additional value of 1 from the "a++". This will stop once 20 < 20; meaning the statement is false. This example is from https://www.tutorialspoint.com/csharp/csharp_while_loop.htm

using System;
namespace Loops
{
  class Program
  {
    static void Main(string[] args)
    {
      /* local variable execution */
      int a = 10;
      
      /* while loop execution */
      while (a < 20)
      {
        Console.Writeline("value of a: {0}", a);
        a++;
      }
      Console.Readline();
    }
  }
}

RESULT:
value of a: 10
value of a: 11
value of a: 12
value of a: 13
value of a: 14
value of a: 15
value of a: 16
value of a: 17
value of a: 18
value of a: 19

6)

int i = 6;
while (i > 3)
{
  Console.Writeline (i--);
}

RESULT: i == 6, 5, & 4

7)

int i = 0;
while (i <= 3)
{
  Console.Writeline (i++);
}

RESULT: i == 0, 1, 2, & 3.

8)

int i = 5;
while (i >= 1)
{
  Console.Writeline (i--);
}

RESULT: i == 5, 4, 3, 2, & 1.

9)


10)

