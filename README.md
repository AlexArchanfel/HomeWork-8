// Напишите программу которая на вход принимает число N, а на выходе показывает все чётные числа от 1 до N  


Console.WriteLine("Введите число ");
int x = int.Parse(Console.ReadLine()!);
int m = 0;
while (m <= x)
{
    Console.WriteLine($"{m}");
    m = m + 2;
}