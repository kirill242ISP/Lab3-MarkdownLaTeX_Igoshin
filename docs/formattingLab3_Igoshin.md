# Форматирование текста в Markdown

**Жирный текст**

*Курсив*

***Жирный курсив***

~~Зачёркнутый~~

`Console.WriteLine("Hello");`

```csharp
string name;
name = Console.ReadLine();
Console.WriteLine(name);

// # Задание: Комментированная программа на C#
//
// Создайте консольное приложение на C#, которое демонстрирует
// все форматы Markdown в комментариях к коду.
//
// ## Требования к программе:
//
// 1. **Имя файла:** FormatDemo.cs
// 2. **Логика:**
//    - Запрашивает у пользователя два числа
//    - Выполняет их сложение
//    - Выводит результаты в форматированном виде
//
// ## Пример работы:
//
// ```
// Введите первое число: 5
// Введите второе число: 7
// Результат: 12
// ```

using System;

class FormatDemo
{
    static void Main()
    {
        // *Запрашиваем первое число*
        Console.Write("Введите первое число: ");
        double number1 = Convert.ToDouble(Console.ReadLine());

        // *Запрашиваем второе число*
        Console.Write("Введите второе число: ");
        double number2 = Convert.ToDouble(Console.ReadLine());

        // ~~Выполняем сложение~~
        double sum = number1 + number2;

        // **Выводим результат**
        Console.WriteLine($"**Результаты операций: {sum}**");
    }
}
using System;

class FormatDemo
{
    static void Main()
    {
        // *Запрашиваем первое число*
        Console.Write("Введите первое число: ");
        double number1 = Convert.ToDouble(Console.ReadLine());

        // *Запрашиваем второе число*
        Console.Write("Введите второе число: ");
        double number2 = Convert.ToDouble(Console.ReadLine());

        // ~~Выполняем сложение~~
        double sum = number1 + number2;

        // **Выводим результат**
        Console.WriteLine($"**Результаты операций: {sum}**");
    }
}