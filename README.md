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
follow an inheritance structure. You will create a Thing class and modify 
Actor and Room to inherit from it. Make a copy of Thing.java and modify your 
existing Actor and Room files. When you're done, copy and paste your code into 
this repository, and upload copies of your new Actor.java and Room.java files.

## Part 3: Container Classes
In this part, you will create the ThingHolder class, which will represent an 
ArrayList of type Thing. Copy and complete the file ThingHolder.java. When 
you're done, copy and paste your code back into this repository.

You will also create the ContainerThing class, which descends from ThingHolder 
but has the additional functionality of being open or closed. Copy and 
complete the file ContainerThing.java. When you're done, copy and paste your 
code into this repository.

## Part 4: Additional Functionality
Additionally, we will add the functionality to take and drop objects. You 
should add "take" and "drop" to your ArrayList of commands. In the Game class, write a
takeObj method, which accepts an Actor, Room, and Treasure, and a dropObj 
method with the same parameters. In each method, move the Treasure from the 
Room to the Actor or vice versa by calling the setter methods for the 
inventory of a Room or Actor.