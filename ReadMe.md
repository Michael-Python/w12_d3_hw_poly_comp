Polymorphism

What does the word 'polymorphism' mean?
	The word polymorphism means 'many forms' or it can be changed from something into something else.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
	Polymorphism allows different objects to be acted on with the same method. The interface decides what gets implemented by a class, the class decides how it gets implemented: you might have a dog and cat class; 
the dog and cat can both 'talk', this method would be written in the interface - String talk();
how the dog and cat would be implemented in their respective classes 
	dog - public String talk(){ return "Woof!";
	cat - public String talk(){ return "Meow!";

What can we use to implement polymorphism in Java?
	 An interface is used to be the change.

How many 'forms' can an object take when using polymorphism?
	How many stars are in the sky?

Give an example of when you could use polymorphism.
	Same as answer 2, I think.

Composition
What do we mean by 'composition' in reference to object-oriented programming?
	Composition is when classes and objects exist in a 'has a' relationship. For instance, it could be that a Car class has an Engine object.

When would you use composition? Provide a simple example in Java.
	I would use composition to increase the functionality of a class:
Public class VideoGame{
	private Player player;
	private HighScore highScore;
Now player and class have parameters that add to the VideoGame class.

What is/are the advantage(s) of using composition?
	A class can also be composed of more than one other case, whereas a class can only inherit from one other. 
	

When an object is destroyed, what happens to all the objects it is composed of?
	They are destroyed.
	