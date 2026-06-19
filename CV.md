# Pavel Fedorov

---

## Education
- University: Belarusian-Russian University, automated information
- English Course: A2+

## About Me
I am a student of the **Belarusian-Russian University** on specialization automated information.  
I am also studying English now.  
I love sports especially **basketball**.

## Skills
- HTML
- CSS
- JavaScript
- C#
- SQL
- Git

## Contacts
- **Location:** Mogilev
- **Phone:** +375255326466
- **Email:** [Pavelfyofarov@gmail.com](mailto:Pavelfyofarov@gmail.com)
- **GitHub:** [My GitHub](https://github.com/pasha2006q)
- **Instagram:** [My Instagram](https://instagram.com/pasha_fedorov4)
- **VK:** [My VK](https://vk.com/id420074817)

## Code Example

```csharp
// Simple example
using System;

class Program
{
    static void Main()
    {
        Random random = new Random();
        Console.WriteLine("Введите размер квадратной матрицы:");
        int n = int.Parse(Console.ReadLine());

        int[,] matrix = new int[n, n];

        for (int i = 0; i < n; i++)
        {
            for (int j = 0; j < n; j++)
            {
                matrix[i, j] = random.Next(0, 11);
            }
        }

        Console.WriteLine("\nСгенерированная матрица:");
        for (int i = 0; i < n; i++)
        {
            for (int j = 0; j < n; j++)
            {
                Console.Write($"{matrix[i, j],4}");
            }
            Console.WriteLine();
        }

        for (int i = 0; i < n; i++)
        {
            bool hasNegative = false;
            int product = 1;

            for (int j = 0; j < n; j++)
            {
                if (matrix[i, j] < 0)
                {
                    hasNegative = true;
                    break;
                }
                product *= matrix[i, j];
            }

            if (!hasNegative)
            {
                Console.WriteLine($"Произведение элементов в строке {i + 1}: {product}");
            }
        }
    }
}
```
## Projects

- **CV Website** - Personal resume website (HTML/CSS)
- **Matrix Calculator** - C# console app for matrix operations
- **Student Database** - SQL database management project

---

© 2026 Pavel Fedorov
