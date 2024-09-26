# Arrays_Properties_Max_-_Min
Escribe un programa para tomar 5 números como entrada, luego calcula y muestra la suma del valor máximo y mínimo ingresados.
class Program
    {
        static void Main(string[] args)
        {
            //your code goes here
          int[]numeros = new int[5];
          int i = 0;
          while (i < 5)
          {
              numeros[i]= Convert.ToInt32(Console.ReadLine());
              i++;
          }
           int max = numeros.Max();
           int min = numeros.Min();
           int suma = max + min;
           Console.WriteLine (suma);

        }
    }
