

## Object-Oriented coding
30/08/2025 (p353 - p359)
### notes

**Inheritance** is a relationship between two classes. **Association** is loosely based on definition of **Inheritance**.

In **Inheritance**, the new class (child/subclass) inherits properties and behaviors from an existing class (parent/superclass). In **Association**, two distinct classes are linked together: they can exist independently.

Etc. A car and its engine vs a customer and his credit card.

**Aggregation** is a special type of more specific **Association.** It can occur when a class is a collection or container of other classes, BUT the contained classes can exist outside of the container. Etc. a team and its players.

**Composition** is a stronger form of **Association**. If the container (NOT a parent/superclass) is destroyed every instance of the contained class is also destroyed. Etc. a hotel and its rooms.

*an example of a container would be a list or a dictionary*

###### Polymorphism

Allows objects of different types to be treated as objects of a common type.

*Etc. Superclass Animal can have subclasses, like Cat and Rodent. All objects in the superclass Animal can execute the methods moveLeft and moveRight.*

###### overriding

Defining a method (inherited from a superclass) with the same name and formal argument types is called overriding. Etc. Animal (superclass)'s method is "move one space", while the method in the subclass Cat is "move three spaces", and the method in the subclass Rodent is "move two spaces".

### answers

Q1: Specify whether each of the following describe aggregation or composition

a) Zoo and Zooanimal: aggregation
b) RaceTrack and TrackSection: composition
c) Department and Teacher: aggregation


Q2: Suppose that tom is an instance of the Cat class, and jerry is an instance of the Mouse class. What will happen when each of these statements is executed?

tom.moveRight() = will move right three spaces
jerry.moveRight() = will move right two spaces


Q3: (ill come back to this later)