using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;


namespace _03032021Diziler
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Kaç sayı üretmek istiyorsunuz");
            byte adet = byte.Parse(Console.ReadLine());
            Random rnd = new Random();
            int rastgele;
            int[] sayilar = new int[adet];
            for (int i = 0; i < sayilar.Length; i++)
            {
                bool dogrula = true;
                rastgele = rnd.Next(10, 100);
                foreach (var x in sayilar)
                {
                    if (x == rastgele)
                    {
                        i--;
                        dogrula = false;
                        break;
                    }
                }
                if (dogrula)
                {
                    sayilar[i] = rastgele;
                }
            }
            Array.Sort(sayilar);
            for (int i = 0; i < sayilar.Length; i++)
            {
                Console.WriteLine(sayilar[i]);
            }
           
        }
    }
}
