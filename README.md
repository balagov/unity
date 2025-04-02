using System;
using System.IO;

class Program
{
    static void Main()
    {
        string filePath = "README.md";
        string content = "Этот проект представляет собой симуляцию ветра, воздействующего на дерево в Unity.";
        
        File.WriteAllText(filePath, content);
        Console.WriteLine("Файл README.md успешно создан и записан.");
    }
}
