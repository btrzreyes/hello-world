# hello-world
/*
 * BATTLE AT BAJO DE MASINLOC
 * by Beatriz Ysabel Reyes, December 20, 2017
 *  
 * This work is a derivative of 
 * "C# Adventure Game" by http://programmingisfun.com, used under CC BY.
 * https://creativecommons.org/licenses/by/4.0/
 */

using System;

namespace Coding_Practice 
{
    class Game{}
    class Item{}
    class Program

    {
        static void Main()
        {
            string CharacterName;

            Console.WriteLine("BATTLE AT BAJO DE MASINLOC");
            Console.WriteLine("Welcome to Bajo de Masinloc You will be exploring the fantastic world of ancienct kingdoms! ");
            Console.WriteLine("What would you like your character's name to be?");
            CharacterName = Console.ReadLine();
            Console.WriteLine("Your character is named " + CharacterName + "!");

            Console.ReadKey();
        }
    }
}
