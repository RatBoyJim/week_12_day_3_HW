# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

An object or class can be given more or different functionality by implementing interfaces.

3. What can we use to implement polymorphism in Java?

Interfaces

4. How many 'forms' can an object take when using polymorphism?

There is no limit.

5. Give an example of when you could use polymorphism.

To add restrictions to specific items. For instance, restricting the sale of items that contain alcohol to customers aged over 18 on an online shop.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Objects have a "has a" or "has" association between each other.

7. When would you use composition? Provide a simple example in Java.

public Computer(int ram, int hddSize, IOutput outputDevice) {
        this.ram = ram;
        this.hddSize = hddSize;
        this.outputDevice = outputDevice;
    }

The computer can utilise any object that uses/fits the criteria of an IOutput interface.

8. What is/are the advantage(s) of using composition?

Clearer, easier to follow and more DRY code.

9. When an object is destroyed, what happens to all the objects it is composed of?

They remain unaffected.