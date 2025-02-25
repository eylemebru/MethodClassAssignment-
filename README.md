 namespace MethodClassAssignment
{
    // Creating a class called MathOperation
    public class MathOperation
    {
        // Method to perform a mathematical operation on the first integer and display the second integer
        public void PerformOperation(int firstNumber, int secondNumber)
        {
            // Perform a math operation on firstNumber (for example: adding 10)
            int result = firstNumber + 10;

            // Display the second number
            Console.WriteLine("The second number is: secondNumber");
            // Display the result of the operation on the first number
            Console.WriteLine("The result of {firstNumber} + 10 is: {result}");
        }
    }

    class Program
    {
        static void Main(string[] args)
        {
            // Instantiate the MathOperation class
            MathOperation operation = new MathOperation();

            // Calling the method and passing in two numbers
            operation.PerformOperation(5, 20);  // First number = 5, Second number = 20

            // Calling the method again by specifying the parameters by name opeation.
            This C# console application demonstrates the use of a class that contains a method performing a mathematical operation on the first integer and displays the second integer.

Features:
- The MathOperation class has two properties (firstNumber and secondNumber).
- The PerformOperation method adds 10 to the firstNumber and displays both the result and the secondNumber.

How to Run:
1. Clone this repository.
2. Open in Visual Studio or any C# IDE.
3. Run the program.

Example usage:
```csharp
operation.PerformOperation(5, 20);
operation.PerformOperation(firstNumber: 15, secondNumber: 30);
```
```


