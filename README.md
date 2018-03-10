# Dungeon-Crawler
Dungeon Crawler is game which encompasses a hero and villains who fight in order to win the game. 
Our game will have various classes the first of which being the Dungeon class
The dungeon class will have an initial size and it will spawn the hero and villains
There will be an abstact class called being which will have all the attributes for the hero and the villains. 
public abstract class Being{
    public int move; //move
    public int attack; // attack
    public int health = 100; // Heath at 100
    public int strength = 50;//attack strength
}
The hero and villain class will exten the being Class
public class Hero extends Being{
    In this class there will be specified health and strength of attack.
}
public class Villian extends Being{
    In this classes there will be specified health. 
}
After we create our dungeon crawler game there will be client/server interaction
The client will interact with the server. 
The server will house the logic of our game. 


              System.out.println("   HERO  ");
            System.out.println("    ____");
            System.out.println("   /    \\");
            System.out.println("  |      |");
            System.out.println("   \\____/   //");
            System.out.println("      |    //");
            System.out.println("     /|\\  // ");
            System.out.println("    / | \\//");
            System.out.println("     / \\");
            System.out.println("    /   \\");
        
             System.out.println("   Villain   ");
            System.out.println("    ____");
            System.out.println("   /    \\");
            System.out.println("  |      |");
            System.out.println("   \\____/   ");
            System.out.println("      |    ");
            System.out.println(" \\   /|\\  / ");
            System.out.println("  \\/ |  \\/  ");
            System.out.println("     / \\");
            System.out.println("    /   \\");   
            
            These are my objects my hero and my villain. 
