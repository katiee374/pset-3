 # PSET 3: Inheritance & Polymorphism
## Part 1: Zoo Management
In this part of the assignment, you will model a zoo, using inheritance 
concepts. You should create an Animal interface, and then create classes 
that descend from that to represent types of animals and species. Additionally,
you will create a Zoo Management driver class to test your code. Complete the 
file Animal.java.
Then, you should create two subclasses for different types of animals (Reptile,
Mammal, Amphibian, etc.). You should then create subclasses of those animal 
types to represent specific species. These subclasses should each have at least
one unique method.
Then, complete ZooManager.java, and draw a UML diagram of your class hierarchy.
Upload a picture of the UML diagram to this repository.

## Part 2: Restructuring the Adventure Game
In this part of the assignment, you should restructure your adventure game to 
follow an inheritance structure. You will create a Treasure class and modify 
Food and Key to inherit from it. You will also create a Thing class and modify 
Treasure and Animal to inherit from it. Treasure will include a value and any 
methods unique to Treasures. Thing will include a name and description, as well 
as anything else commmon between Treasures and Animals. 
You should add an ArrayList<Thing> to your Room class to represent the animals 
or other objects in the Room.
When you're done, upload copies of your updated files to this repository.

## Part 3: Container Classes
In this part, you will create the TreasureChest class, which will represent a 
collection of Treasures. It will have an ArrayList of Treasures as well as boolean 
fields representing whether or not the chest is open or openable. You should add 
an ArrayList<TreasureChest> to your Room class to represent the chests in each 
room, and initialize them in your Game class.

When you're done, upload your updated files to this repository.

## Part 4: Additional Functionality
Additionally, we will add the functionality to take and drop objects. In the 
Game class, write a takeObj method, which accepts an Actor, Room, and 
Treasure, and a dropObj method with the same parameters. In each method, move 
the Treasure from the Room to the Actor or vice versa by calling the setter 
methods for the inventory of a Room or Actor.