# Caracter_Mayuscula
Programa que lea un carácter por teclado y compruebe si es una letra mayúscula
using System;

namespace Caracter_Mayuscula
{
    class Program
    {
        static void Main(string[] args)
        {
            char letra;

            Console.Write("Ingrese un caracter: ");
            letra = Convert.ToChar(Console.ReadLine());

            if (letra >= 'a' && letra <= 'z')
            {
                Console.WriteLine("El caracter ingresado es Minuscula");

            }else if (letra >= 'A' && letra <= 'Z')
            {
                Console.WriteLine("El caracter ingresado es Mayuscula");
            }else
            {
                Console.WriteLine("El caracter ingresado no es una letra");
            }

        }
    }
}
