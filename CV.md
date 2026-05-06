<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My CV</title>
</head>

<body > 

<header align="center">
    <svg width="180" height="180">
    <defs>
        <clipPath id="circleClip">
            <circle cx="90" cy="90" r="90"/>
        </clipPath>
    </defs>
    <image href="photo.png" width="180" height="180" clip-path="url(#circleClip)"/>
</svg >
    
</header>
    
    <h1 style="color: red;">Pavel Fedorov</h1>
</header>

<hr>

<main>
    <section>
        <h2>Education</h2>
        <ul>
            <li>University: Belarusian-Russian University, automated information</li>
            <li>English Course: A2+</li>
        </ul>
    </section>

    <section>
        <h2>About Me</h2>
        <p>
           I am a student of the <strong>Belarusian-Russian University</strong> on specialization automated information. 
          <br> I am also studying English now. 
           <br>I love sports especially <strong>basketball</strong>. 
        </p>
    </section>

    <section>
        <h2>Skills</h2>
        <ul>
            <li style="color: blue;">HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>C#</li>
            <li>SQL</li>
            <li>Git</li>
        </ul>
    </section>

    <section>
        <h2>Contacts</h2>
        <ul>
            <li><strong>Location:</strong> Mogilev</li>
            <li><strong>Phone:</strong> +375255326466</li>
            <li><strong>Email:</strong> <a href="mailto:Pavelfyofarov@gmail.com">Pavelfyofarov@gmail.com</a></li>
            <li><strong>GitHub:</strong> <a href="https://github.com/pasha2006q">My GitHub</a></li>
            <li><strong>Instagram:</strong> <a href="https://instagram.com/pasha_fedorov4">My Instagram</a></li>
            <li><strong>VK:</strong> <a href="https://vk.com/id420074817">MY VK</a></li>
        </ul>
    </section>

    <section>
        <h2>Code Example</h2>
        <div>
            <pre>
<code>
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

        for (int i = 0; i &lt; n; i++)
        {
            for (int j = 0; j &lt; n; j++)
            {
                matrix[i, j] = random.Next(0, 11);
            }
        }

        Console.WriteLine("\nСгенерированная матрица:");
        for (int i = 0; i &lt; n; i++)
        {
            for (int j = 0; j &lt; n; j++)
            {
                Console.Write($"{matrix[i, j],4}");
            }
            Console.WriteLine();
        }

        for (int i = 0; i &lt; n; i++)
        {
            bool hasNegative = false;
            int product = 1;

            for (int j = 0; j &lt; n; j++)
            {
                if (matrix[i, j] &lt; 0)
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
</code>
            </pre>
        </div>
    </section>

    <section>
        <h2>Projects</h2>
        <p>CV.</p>
    </section>
</main>

<hr>

<footer>
    <p>© 2026 Pavel Fedorov</p>
    <nav>
        <a href="https://github.com/pasha2006q">GitHub</a> |
        <a href="https://instagram.com/pasha_fedorov4">Instagram</a> |
        <a href="https://vk.com/id420074817">VK</a>
    </nav>
</footer>

</body>
</html>



<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My CV</title>
   
</head>


    <h1 style="color: #2c3e50; font-family: Arial, sans-serif;">Pavel Fedorov</h1>
   
