# Minun ensimmäinen repositorio
Osaan nyt luoda uuden repositorion ja lähettää sen **GitHub**iin

## Käyttöohjeet
Tähän voisin lisätä käyttöohjeet projektille.

## Koodin esittely
Tällä tavalla voin esitellä koodia jolloin se on myös helppoa kopioida
```

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp5
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Paljono sinulla on rahaa? ");
            int raha = Convert.ToInt32(Console.ReadLine());

            if (raha < 10)
            {
                Console.Write("Haluatko ottaa lainaa? ");
                Console.WriteLine("Vastaa 1 jos haluat ottaa lainaa");
                Console.WriteLine("Vastaa 2 jos et halua ottaa lainaa");

                string vastaus = Console.ReadLine();

                if (vastaus == "1")
                {
                    Console.WriteLine("Otat lainaa");
                }
                else if (vastaus == "2")
                {
                    Console.WriteLine("Et ota lainaa");
                }
                else
                {
                    Console.WriteLine("Virheellinen valinta");
                }
            }
            else
            {
                Console.WriteLine("Sinulla on tarpeeksi rahaa, et tarvitse lainaa.");
                

            }
            Console.ReadKey();
        }  
    }
}

    




```


