// i stopped at this lesson http://programmingisfun.com/learn/c-sharp-adventure-game/c_sharp_06_refactoring/
/*
 * BATTLE AT BAJO DE MASINLOC
 * by Beatriz Ysabel Reyes, December 20, 2017
 *  
 * This work is a derivative of 
 * "C# Adventure Game" by http://programmingisfun.com, used under CC BY.
 * https://creativecommons.org/licenses/by/4.0/
 */

using System;
/*using System.Threading; for movement in the title*/

namespace Coding_Practice
{
    public static class Game { } // public static for game class update
    class Item{}
    class Program

    {
        static void Main()
        {
            string CharacterName;
            string title = @" ____   ____ ______ ______ _       ___       ____ ______                                        
|    \ /    |      |      | |     /  _]     /    |      |                                       
|  o  )  o  |      |      | |    /  [_     |  o  |      |                                       
|     |     |_|  |_|_|  |_| |___|    _]    |     |_|  |_|                                       
|  O  |  _  | |  |   |  | |     |   [_     |  _  | |  |                                         
|     |  |  | |  |   |  | |     |     |    |  |  | |  |                                         
|_____|__|__| |__|   |__| |_____|_____|    |__|__| |__|                                         
                                                                                                
 ____   ____  ____  ___       ___     ___      ___ ___  ____  _________ ____  _      ___     __ 
|    \ /    ||    |/   \     |   \   /  _]    |   |   |/    |/ ___/    |    \| |    /   \   /  ]
|  o  )  o  ||__  |     |    |    \ /  [_     | _   _ |  o  (   \_ |  ||  _  | |   |     | /  / 
|     |     |__|  |  O  |    |  D  |    _]    |  \_/  |     |\__  ||  ||  |  | |___|  O  |/  /  
|  O  |  _  /  |  |     |    |     |   [_     |   |   |  _  |/  \ ||  ||  |  |     |     /   \_ 
|     |  |  \  `  |     |    |     |     |    |   |   |  |  |\    ||  ||  |  |     |     \     |
|_____|__|__|\____|\___/     |_____|_____|    |___|___|__|__| \___|____|__|__|_____|\___/ \____|"; // for ASCII things, i think "@" is used to extend the code in sveral lines
            
            /*string LoadingText = "Loading...";// used in collaboration with System.Threading
            string TitleBarText = ""; // used in collaboration with System.Threading
            bool Loading = true; // used in collaboration with System.Threading

            Console.Title = TitleBarText; // look at when the app runs, how "Loading" is moving
            while (Loading)
            {
                for (int i = 0; i < LoadingText.Length; i++)
                {
                    TitleBarText = TitleBarText + LoadingText[i];
                    Console.Title = TitleBarText;
                    Thread.Sleep(240);
                }
                TitleBarText = "";

            }*/

            Console.Title = "Welcome"; //For title when it is played
            Console.WriteLine(title); // to put the ASCII, note to use ASCII set a width and height
            Console.ReadKey(); // waits for enter before chaging a title
            Console.Title = "Battle of Bajo de Masinloc"; //changed title
            Console.Clear(); //used to clear the screen

            Console.WriteLine("BATTLE AT BAJO DE MASINLOC");
            Console.WriteLine("Welcome to Bajo de Masinloc You will be exploring the fantastic world of ancienct kingdoms! ");
            Console.ReadLine();

            Console.Title = "Character Creation"; // To tell the user that this is the character creation part
            Console.WriteLine("What would you like your character's name to be?");
            CharacterName = Console.ReadLine();
            Console.WriteLine("Your character is named " + CharacterName + "!");

            Console.Title = "Battle at Bajo de Masinloc"; // Tells user that this is the title

            Console.ReadKey();
        }
    }
}
