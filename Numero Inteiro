using System;

public class Program
{
    public static void Main()
    {
        int negativos = 0, positivos = 0, zeros = 0;
        
        Console.WriteLine("Digite 5 números:");
        
        for(int i = 1; i <= 5; i++)
        {
            Console.Write("Número " + i + ": ");
            double num = Convert.ToDouble(Console.ReadLine());
            
            if(num < 0)
                negativos++;
            else if(num > 0)
                positivos++;
            else
                zeros++;
        }
        
        Console.WriteLine("\nResultado:");
        Console.WriteLine("Negativos: " + negativos);
        Console.WriteLine("Positivos: " + positivos);
        Console.WriteLine("Zeros: " + zeros);
    }
}
