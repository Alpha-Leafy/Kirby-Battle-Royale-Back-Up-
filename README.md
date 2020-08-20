# Kirby-Battle-Royale-Back-Up-

 //Dont Look Just Press Start 
           
            Console.Title = "Kirby Battle Royale";

            
            Console.ForegroundColor = ConsoleColor.Magenta;
            

            //Title of program
            Console.WriteLine("Hello, Welcome to Kirby Battle Royale\n");
            
            Console.WriteLine("Username:");

            string username = Console.ReadLine();

            Console.WriteLine("Password:");

            Console.ReadLine();

            Console.WriteLine("Welcome " + username + ", Press ENTER button to Join a Battle");

            Console.ReadLine();

            Console.WriteLine("Your on the battle bus (Press ENTER)");

            Console.ReadLine();

            Console.WriteLine("3 2 1 Go! Go! Go! (Press ENTER)");

            Console.ReadLine();

            Console.WriteLine("You Landed in Dededes Castle, Enter, or Leave ");

            Console.ReadLine();

            Console.WriteLine("Pick you're decision wisely || Enter = Press 1 || Leave = Press 2");

            int one = Convert.ToInt32(Console.ReadLine());


            if(one == 1)
            {
                Console.WriteLine("You Accelarate into His Castle and and Hide behind the door");

                Console.ReadLine();

                Console.WriteLine("You hear big large footsteps, coming towards you, closer and closer");

                Console.ReadLine();

                Console.WriteLine("Run away or Shoot Him || Shoot = Press 1 || Run Away = Press 2");
                int two = Convert.ToInt32(Console.ReadLine());

                if (two == 1)
                {
                    Console.WriteLine("You try to shoot, BuT tHE sHotGuN HaD No AMm0, King Dedede Had a Rocket Laucher and blow you up into pieces");


                }
                else
                {
                    Console.WriteLine("You Run away as fast as possible, while you run you turn you see King Dedede staring at you, \n as you run out you see ShotGun ammo on the floor, you pick it up,\n oh its a grenade");

                    Console.ReadLine();

                    Console.WriteLine("Its about to blow up in 10 seconds what do you do..? || Pick it up = Press 1 || Throw = Press 2");
                    int three = Convert.ToInt32(Console.ReadLine());

                    if(three == 1)
                    {
                        Console.WriteLine("yOUR stuPId, Y0u'll pick up a grenade...?, you die, GAME OOOOOOVER!!!");
                    }
                    else
                    {
                        Console.WriteLine("You throw it away and once it thrown away blood splatters, You Killed Waddle Dee!");

                        Console.ReadLine();

                        Console.WriteLine("Waddle Dee dropped some ShotGun Amm0, You pick it up and Reliaze that King Dedede is Chasing after you");

                        Console.ReadLine();

                        Console.WriteLine("You Shoot him in the head, 2 Kills");

                        Console.ReadLine();

                        Console.WriteLine("Oh yeaaaaaaah......");

                        Console.ReadLine();

                        Console.WriteLine("I forgot to tell you...");

                        Console.ReadLine();

                        Console.WriteLine("The Storm is catching up");

                        Console.ReadLine();

                        Console.WriteLine("You Run Like a blue hedgehog running around..but there are to paths infront of you");

                        Console.ReadLine();

                        Console.WriteLine("Take Walthamstow Path or Kirb Path...? || Walthamstow Road =  Press 1 || Kirb = Press 2");
                        int four = Convert.ToInt32(Console.ReadLine());

                        if(four == 1)
                        {
                            Console.WriteLine("You Take Walthamstow Path.");

                            Console.WriteLine("You See Meta Knight, Running as the storm chases you and him, You Get Closer");

                            Console.ReadLine();

                            Console.WriteLine("He Doesn't Know Your Behind Him, Shoot Him From behind or Run Past Him...");

                            Console.ReadLine();

                            Console.WriteLine("Choose Wisely || Shoot Him = Press 1 || Run Past Him = Press 2 ");
                            int five = Convert.ToInt32(Console.ReadLine());

                            if(five == 1)
                            {
                                Console.WriteLine("You Shoot Him and he dies");

                            }
                            else
                            {
                                Console.WriteLine("You Run Past as Quickly as Possible but...He slices you in half with his sword, You Die....");
                            }





                        }
                        else
                        {
                            Console.WriteLine("You Take Kirb Path");

                            Console.ReadLine();

                            Console.WriteLine("You Run As Fast as you can...");

                            Console.ReadLine();

                            Console.WriteLine("You Get to the of the path and you see Meta Knight coming after you.");

                            Console.ReadLine();

                            Console.WriteLine("Theres a Rock beside You..on the right..but Meta Knight about to use an attack");

                            Console.WriteLine("You Have to Dodge...|| Dodge Left = Press 1 || Dodge Right = Press 2 ");
                            int five = Convert.ToInt32(Console.ReadLine());

                            if(five == 1)
                            {
                                Console.WriteLine("Good, You were listening");

                                Console.ReadLine();

                                Console.WriteLine("You Dodge to the left and You use the Hammer to Hit away into the stars");

                                Console.ReadLine();

                                Console.WriteLine("Out Of The Park!");

                                Console.ReadLine();

                                Console.WriteLine("Home Run!");

                                Console.ReadLine();

                                Console.WriteLine("There 10 people left and You see Jinx In the Air Flying in the air...");

                                Console.ReadLine();

                                Console.WriteLine("Shoot Him...Or Ignore Him... || Shoot Him = Press 1 || Ignore Him = Press 2");
                                int six = Convert.ToInt32(Console.ReadLine());

                                if(six == 1)
                                {
                                    Console.WriteLine("Are You Dumb...A sh0TguN Ia nOT a SnIpeR..Jinx hears the sound and makes a black hole sucking everyone in...He WON..");

                                    Console.ReadLine();

                                    Console.WriteLine("Every Died because you were too stupid that you thought that a Sh0tGuN Was tHe SamE as A SNIpEr");
                                }
                                else
                                {
                                    Console.WriteLine("You ignore him and keep running to avoid the storm..");

                                    Console.ReadLine();

                                    Console.WriteLine(".....");

                                    Console.ReadLine();

                                    Console.WriteLine(".......");

                                    Console.ReadLine();

                                    Console.WriteLine(".......");

                                    Console.ReadLine();

                                    Console.WriteLine(".......");

                                    Console.ReadLine();

                                    Console.WriteLine("........");

                                    Console.ReadLine();

                                    Console.WriteLine(".........");

                                    Console.ReadLine();

                                    Console.WriteLine("........");

                                    Console.ReadLine();

                                    Console.WriteLine("......KaBoooooom!!");













                                }






                            }
                            else
                            {
                                Console.WriteLine("You Dont Listen....");

                                Console.ReadLine();

                                Console.WriteLine("I said There was a rock..on your RIGHT!!!");

                                Console.ReadLine();

                                Console.WriteLine("You reflect of the wall into the direction of Meta Knights Direction and he hits you All the way back to Africa");

                                Console.ReadLine();

                                Console.WriteLine("Out Of The Park!!!");
                            }











                        }













                    }

                }


            }
            else
            {
                Console.WriteLine("King Dedede was standing right behind you and slapped you to death");

                Console.ReadLine();

                Console.WriteLine("You die and at your funeral people are doing the coffin dance");

             
           
            }

         

         

          
            Console.ReadKey();
        }
    }
}
