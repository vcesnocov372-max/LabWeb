# Anton Chesnokov
**Junior C# Developer** | Data Analysis | Learning Programming

📍 Minsk, Belarus  
📧 anton.chesnokov@example.com  
📅 2026 · Actively looking for an internship / Junior position

---

## 👨‍💻 About Me

I am a beginner C# developer. I like to structure data, write clean code, and understand algorithms. I improve my skills every day, practice regularly, and solve small problems. I can work with collections, loops, and basic statistics.

---

## 💻 Code Example (working with a list of numbers)

Below is a C# program I wrote. It shows how to use `List<int>`, calculate the sum, and find the average.

```csharp
class Program
{
    static void Main()
    {
        List<int> numbers = new List<int>() { 1, 2, 3, 4, 5 };
        
        Console.WriteLine("Vector elements: ");
        foreach(int num in numbers)
        {
            Console.Write(num + " ");
        }
        Console.WriteLine();
        
        // Calculate sum
        int sum = 0;
        for(int i = 0; i < numbers.Count; i++)
        {
            sum += numbers[i];
        }
        
        Console.WriteLine("Sum of elements: " + sum);
        Console.WriteLine("Average: " + (double)sum / numbers.Count);
    }
}
