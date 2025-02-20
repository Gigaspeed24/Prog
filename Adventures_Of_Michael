#include <iostream>
#include <string>
#include <limits>

void printCentered(const std::string& text, int consoleWidth) {

    int padding = (consoleWidth - text.length()) / 2;

    if (padding > 0) {

        std::cout << std::string(padding, ' ') << text << std::endl;

    } else {

        std::cout << text << std::endl; // If text is longer than console width

    }

}

int main () {

    const int consoleWidth = 230;

    system("CLS");

    std::cout << "\n\n\n\n\n\n";

    printCentered("|      ~~~~~~~~~~~~~~~~~~~~~      |", consoleWidth);
    printCentered("|      Adventures of Michael      |", consoleWidth);
    printCentered("|      ~~~~~~~~~~~~~~~~~~~~~      |", consoleWidth);
    std::cout << "\n\n\n";
    printCentered("Michael the sand-loving explorer travels through the dunes of his beloved home: Egypt.", consoleWidth);
    printCentered("After a long hunt for adventures he passed upon a hidden cave-entrance inside a ravine.", consoleWidth);
    std::cout << "\n\n\n\n\n\n";
    printCentered("[1] Climb down the ravine and enter the cave.", consoleWidth);
    printCentered("[2] Travel on and search for another adventure.", consoleWidth);
    std::cout << "\n\n\n";

    int choice1 = 0;
    std::string dummy;

    // First Choice begin

    do  {

        std::cout << "\n\n\n";
        printCentered("> ", consoleWidth);
        std::cin >> choice1;

        if (std::cin.fail()) {

                std::cin.clear(); // Clear the error flag
                std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n'); // Ignore invalid input
                choice1 = 0; // Reset choice1 to ensure the loop continues

        }

    } while (choice1 != 1 && choice1 != 2);

    if (choice1 == 1)  {

        // Second choice begin

        system("CLS");

        int choice2 = 0;

        std::cout << "\n\n\n\n\n\n";
        printCentered("You squeezed through the narrow ravine made of sandstone and rock.", consoleWidth);
        printCentered("Entering the cave you hear absolute silence and no light is shining.", consoleWidth);
        std::cout << "\n\n\n\n\n\n";
        printCentered("[1] Turn around and try to climb up.", consoleWidth);
        printCentered("[2] Move forward.", consoleWidth);
        std::cout << "\n\n\n";

        do  {

            std::cout << "\n\n\n";
            printCentered("> ", consoleWidth);
            std::cin >> choice2;

            if (std::cin.fail()) {

                std::cin.clear();
                std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
                choice2 = 0;

            }

        } while (choice2 != 1 && choice2 != 2);

        if (choice2 == 1) {

            system("CLS");

            std::cout << "\n\n\n\n\n\n";
            printCentered("As you take a few steps back to the ravine you hear a loud rumbling.", consoleWidth);
            printCentered("The rocks you climbed through ruptured, covering the exit.", consoleWidth);
            printCentered("It is completely dark and you try to find a way through the cave.", consoleWidth);
            std::cout << "\n\n\n\n\n\n";
            printCentered("[Press any character]", consoleWidth);
            std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
            std::getline(std::cin, dummy);

        }

            else{

            }

    }

      // Second Choice end

    else  {

        system("CLS");

        std::cout << "\n\n\n\n\n\n";
        printCentered("You take your first few steps away from the ravine.", consoleWidth);
        printCentered("As you already felt regret of passing by an adventure you feel the ground becoming uneasy.", consoleWidth);
        printCentered("The ground underneath began to swirl and the sand sucked you in.", consoleWidth);
        printCentered("After dusting yourself off, you find yourself in the same cave you walked away from.", consoleWidth);
        std::cout << "\n\n\n\n\n\n";
        printCentered("[Press any character]", consoleWidth);
        std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
        std::getline(std::cin, dummy);

    }
      
    // First choice end

    // Third choice begin

    system("CLS");

    int choice3 = 0;

    std::cout << "\n\n\n\n\n\n";
    printCentered("You stumble in the dark, but after a bit of time passed you see a glimmer of light shining in the distance.", consoleWidth);
    printCentered("Without thinking you carefully take step by step forward until you reach the light.", consoleWidth);
    printCentered("Before you is a giant door, which through the middle has a slight crack, peeking with light.", consoleWidth);
    std::cout << "\n\n\n\n\n\n";
    printCentered("[1] Try to push open the door.", consoleWidth);
    printCentered("[2] Try peeking through the door.", consoleWidth);
    std::cout << "\n\n\n";

    do  {

        std::cout << "\n\n\n";
        printCentered("> ", consoleWidth);
        std::cin >> choice3;

        if (std::cin.fail()) {

            std::cin.clear();
            std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
            choice3 = 0;

        }

    } while (choice3 != 1 && choice3 != 2);

    if (choice3 == 1)   {

        // First Convo start

        system("CLS");

        int convo1 = 0;

        std::cout << "\n\n\n\n\n\n";
        printCentered("You take a step back and abruptly start running towards the door and throw your whole weight against it.", consoleWidth);
        printCentered("The door makes a loud noise, but doesn't move in the slightest.", consoleWidth);
        printCentered("Suddenly you hear screaming from behind.", consoleWidth);
        printCentered("You see a small-looking creature with a magical staff standing behind you.", consoleWidth);
        printCentered("[Unknown]: WHAT ARE YOU DOING???", consoleWidth);
        std::cout << "\n\n\n\n\n\n";
        printCentered("[1] Who are you?", consoleWidth);
        printCentered("[2] I tried going through the door, I got stuck in the cave and there is nowhere else to go.", consoleWidth);
        printCentered("[3] What is this staff your holding?", consoleWidth);
        std::cout << "\n\n\n";

        do  {

            std::cout << "\n\n\n";
            printCentered("> ", consoleWidth);
            std::cin >> convo1;

            if (std::cin.fail()){
                std::cin.clear();
                std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
                convo1 = 0;

            }

        } while (convo1 != 1 && convo1 != 2 && convo1 != 3);

        if(convo1 == 1 || convo1 == 2 || convo1 == 3){

            system("CLS");

            std::cout << "\n\n\n\n\n\n";
            printCentered("[Unknown]: I'm not talking to you NOW?! This is your fault. Take this and fight for your life.", consoleWidth);
            printCentered("The unknown creature throws the staff to you and runs off into a small hole, you wouldn't fit through.", consoleWidth);
            printCentered("You caught the staff and you felt the magical power overcoming you.", consoleWidth);
            printCentered("The door rattles.. then a fast heavy heap and you see the giant snake piercing the door, slithering out.", consoleWidth);
            std::cout << "\n\n\n\n\n\n";
            printCentered("[Press any character]", consoleWidth);
            std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
            std::getline(std::cin, dummy);

            // First convo end

        }

    }
    
    else    {

        // Second Convo begin

        system("CLS");

        int convo2 = 0;

        std::cout << "\n\n\n\n\n\n";
        printCentered("You peek through the door and you begin to freeze upon the sight of a giant snake chained in a huge room.", consoleWidth);
        printCentered("The colossal snake, picks up your scent and hisses so loud, that your head starts clinging.", consoleWidth);
        printCentered("You hear running behind you, you turn around and see a little creature running towards the door with a magical staff.", consoleWidth);
        printCentered("[Unknown]: The snake woke up. You have unlucky timing, but I'll guard this door with my life now.", consoleWidth);
        std::cout << "\n\n\n\n\n\n";
        printCentered("[1] Who are you?", consoleWidth);
        printCentered("[2] Let me help you!", consoleWidth);
        std::cout << "\n\n\n";

        do {

            std::cout << "\n\n\n";
            printCentered("> ", consoleWidth);
            std::cin >> convo2;

            if (std::cin.fail()){
                std::cin.clear();
                std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
                convo2 = 0;

            }

        } while (convo2 != 1 && convo2 != 2);

        if (convo2 == 1)    {

            system("CLS");

            std::cout << "\n\n\n\n\n\n";
            printCentered("[Glorbal]: I am Glorbal the Door Warden, behind these doors, an ancient and evil snake has been held ca--", consoleWidth);
            printCentered("Just as he tried to introduce himself to you, the snake broke their chains and broke the doors with her head.", consoleWidth);
            std::cout << "\n\n\n\n\n\n";
            printCentered("[Press any character]", consoleWidth);
            std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
            std::getline(std::cin, dummy);

        }

        else    {

            system("CLS");

            std::cout << "\n\n\n\n\n\n";
            printCentered("[Unknown]: There is NO way you can help me fighting this giant snake! The only way is with thi--", consoleWidth);
            printCentered("Just as he tried to explain to you how to defeat this evil, the snake broke their chains and broke the doors with her head.", consoleWidth);
            std::cout << "\n\n\n\n\n\n";
            printCentered("[Press any character]", consoleWidth);
            std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
            std::getline(std::cin, dummy);

        }

        // Second convo end

        system("CLS");

        // Fourth choice begin

        int choice4 = 0;

        std::cout << "\n\n\n\n\n\n";
        printCentered("The wardens body got pierced and his lifeless body knees to the floor, but his hands still gripped tightly around the staff.", consoleWidth);
        printCentered("The snake locks its view onto you and charges up an attack.", consoleWidth);
        std::cout << "\n\n\n\n\n\n";
        printCentered("[1] Run towards the body and take his wand", consoleWidth);
        printCentered("[2] Jump to the side to try and dodge the attack.", consoleWidth);
        std::cout << "\n\n\n";

        do {

            std::cout << "\n\n\n";
            printCentered("> ", consoleWidth);
            std::cin >> choice4;

            if (std::cin.fail()){
                std::cin.clear();
                std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
                choice4 = 0;

            }
            
        } while (choice4 != 1 && choice4 !=2);

        if (choice4 == 1)  {

            system("CLS");

            std::cout << "\n\n\n\n\n\n";
            printCentered("The snake heaps into your direction with their fangs targeting you.", consoleWidth);
            printCentered("You barely escaped his sharpened fangs and grabbed the wand.", consoleWidth);
            printCentered("Suddenly you feel a heap of magical power overcoming your body.", consoleWidth);
            std::cout << "\n\n\n\n\n\n";
            printCentered("[Press any character]", consoleWidth);
            std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
            std::getline(std::cin, dummy);

        }

        else    {

            system("CLS");

            std::cout << "\n\n\n\n\n\n";
            printCentered("You tried dodging to the side, but the snakes reaction was quicker than your movement.", consoleWidth);
            printCentered("The huge snake pushes their teeth between your body and you die instantly.", consoleWidth);
            std::cout << "\n\n\n\n\n\n";
            printCentered("GAME OVER", consoleWidth);

            return 0;

        }

        // Fourth choice end

    }

    // Third choice end

    // Fith choice start

    system("CLS");

    int choice5 = 0;

    std::cout << "\n\n\n\n\n\n";
    printCentered("The snake is looking straight at you, locking its eyes on you. You see it showing it's fangs, dripping venoms from its tip.", consoleWidth);
    printCentered("You know this is a battle you cannot escape.", consoleWidth);
    printCentered("After a glimpse of a second the snake's head charges towards you.", consoleWidth);
    std::cout << "\n\n\n\n\n\n";
    printCentered("[1] Quickly lay on the ground, hoping it misses you slightly.", consoleWidth);
    printCentered("[2] Stick the staff inside the mouth as it leaps.", consoleWidth);
    printCentered("[3] Dodge quickly to the side.", consoleWidth);
    std::cout << "\n\n\n";

    do {

        std::cout << "\n\n\n";
        printCentered("> ", consoleWidth);
        std::cin >> choice5;

        if (std::cin.fail()){
            std::cin.clear();
            std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
            choice5 = 0;

        }

    } while (choice5 != 1 && choice5 != 2 && choice5 != 3);


    if (choice5 == 1)   {

        // Sixth choice start

        system("CLS");

        int choice6 = 0;

        std::cout << "\n\n\n\n\n\n";
        printCentered("You laid down on the ground, just as the snake tried to attack you. Miraculously the snake missed you by an inch.", consoleWidth);
        printCentered("The snake turns around and charges another attack instantly.", consoleWidth);
        printCentered("You still lay on the ground and have limited options.", consoleWidth);
        std::cout << "\n\n\n\n\n\n";
        printCentered("[1] Take the staff and hold it up in the air, hoping you can channel your power just in time.", consoleWidth);
        printCentered("[2] Throw the staff in the snakes mouth.", consoleWidth);
        std::cout << "\n\n\n";

        do {

            std::cout << "\n\n\n";
            printCentered("> ", consoleWidth);
            std::cin >> choice6;
    
            if (std::cin.fail()){
                std::cin.clear();
                std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
                choice6 = 0;
    
            }

        }    while (choice6 != 1 && choice6 != 2);

        if (choice6 == 1)   {

            system("CLS");

            std::cout << "\n\n\n\n\n\n";
            printCentered("The giant snake opens its mouth, trying to rip your body apart.", consoleWidth);
            printCentered("You stick out your magical staff inside its mouth as it almost reaches you.", consoleWidth);
            printCentered("The snake suddenly freezes, the staff is starting to glow very brightly, every second more.", consoleWidth);
            printCentered("It collapses with its whole weight to the ground. No movement. The staff saved your life and took the life of this predator.", consoleWidth);
            std::cout << "\n\n\n\n\n\n";
            printCentered("VICTORY", consoleWidth);

            return 0;

        }

        else    {

            system("CLS");

            std::cout << "\n\n\n\n\n\n";
            printCentered("You threw the staff inside the snakes mouth as it attacked.", consoleWidth);
            printCentered("The staff has no magical reaction. You just threw a stick inside its mouth.", consoleWidth);
            std::cout << "\n\n\n\n\n\n";
            printCentered("GAME OVER", consoleWidth);
            
            return 0;

        }

        // Sixth choice end

    }

    else if (choice5 == 2)  {

        system("CLS");

        std::cout << "\n\n\n\n\n\n";
        printCentered("The giant snake opens its mouth, trying to rip your body apart.", consoleWidth);
        printCentered("You stick out your magical staff inside its mouth as it almost reaches you.", consoleWidth);
        printCentered("The snake suddenly freezes, the staff is starting to glow very brightly, every second more.", consoleWidth);
        printCentered("It collapses with its whole weight to the ground. No movement. The staff saved your life and took the life of this predator.", consoleWidth);
        std::cout << "\n\n\n\n\n\n";
        printCentered("VICTORY", consoleWidth);

        return 0;

    }

    else {

        system("CLS");

        std::cout << "\n\n\n\n\n\n";
        printCentered("You tried jumping to the side to dodge the attack.", consoleWidth);
        printCentered("The snake misses you, but quickly turns around, striking you again.", consoleWidth);
        printCentered("You have no option but to look in the snakes eyes, meanwhile you meet your certain death.", consoleWidth);
        std::cout << "\n\n\n\n\n\n";
        printCentered("GAME OVER", consoleWidth);

        return 0;

    }
    
    // Fith choice ends

    return 0;

}
