# Darina Ivanova

> Read the world through the eyes of the heart

---

## 📞 Contact Information

- **Telephone**: +375 (33) 308-71-10
- **Email**: [ivanova.darina.pir241@mail.ru](mailto:ivanova.darina.pir241@mail.ru)
- **Instagram**: [@daarinka_i](https://www.instagram.com/daarinka_i)

---

## 👤 About Me

I'm a second-year student at the **Belarusian-Russian University**. I'm in my second year of studying in the **Electrical Engineering Department**, majoring in **Software Engineering**.

---

## 💻 Skills

- **Programming Languages**: C#
- **Databases**: Microsoft Access
- **Tools**: Visual Studio
- **Version Control**: Git, GitHub

---

## 💡 Code Example

```csharp
Random random = new Random();
Console.Write("Введите размер массива: ");
int n = Convert.ToInt32(Console.ReadLine());
int[] array = new int[n];

for (int i = 0; i < array.Length - 1; i++)
{
    for (int j = 0; j < array.Length - 1 - i; j++)
    {
        array[i] = random.Next(-10, 10);
    }
}
Console.WriteLine("Начальный массив: " + string.Join(" ", array));