# Tasks

● You should not support only plates; you should support other shapes (you should
have a class Shape). The shapes classes should be dynamically loaded at the start
of the execution from a specific folder. You should support at least two shapes.


● You must have more than one kind of falling object (ex: plates, bombs, ... etc)


● These shapes must be loaded dynamically into the game before the user can
start playing, either from a specific general path as (Documents or any other
general path), or a specific folder by the user choice.


● The user gets a point when he collects three consecutive shapes from the same
color (even if they are different shapes).


● You should use (at least) 5 design patterns in your design from the following


1. Singleton
2. Factory or Pool
3. Iterator
4. Dynamic Linkage
5. Snapshot
6. State
7. Strategy
8. Flyweight
9. Observer

This assignment mainly tackles the application of the design patterns you studied
during the course, so you are supposed to give time for the design.
You should of course use MVC.



● You need to support at least 3 levels of difficulties, but you are free to choose any
criteria for difficulty (e.g., different speed, multiple clowns, more queues,
changing plates colors or sizes, etc.).


● You are provided with a custom game engine that supports three types of
objects: movable, constant and user-controlled objects.
Note: you may have look on the sample game on this link see how the engine is
included, and how the sample game interacts with the game engine



● Two interfaces define the interaction with the game engine:
1. World: defines a level of the game and its objects
2. GameObject: an object of the game, it could be a shape, clown, etc.
# Report
The report should contain the following:



● Class diagram of your design.


● Section for each pattern (the required and any other patterns you used) and
how you used it in your design, and a class diagram explaining this.
