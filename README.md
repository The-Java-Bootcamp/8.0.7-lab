# Lab: 8.0.7

**Objective:**

- Understand the concept and importance of inheritance in Java development.
- Learn how to implement inheritance using Java's extends keyword and super() method.
- Explore practical applications of inheritance in real-world Java projects.
- Identify common pitfalls and best practices when working with inheritance.
- Gain hands-on experience with a complete Java example that demonstrates inheritance.

**Prerequisites:**

- Basic understanding of Java programming.
- Familiarity with creating classes and objects in Java.
- Understanding of basic object-oriented programming concepts.

**What You'll Achieve:**

- Develop a solid understanding of inheritance in Java.
- Implement practical examples that can be applied in real-world scenarios.
- Enhance your skills in object-oriented programming and class hierarchies.

**Assignment Details**

In this assignment, you'll expand on the Transformers theme by creating a class hierarchy. Follow these steps:

1. Create a base class named `Transformer` with the following attributes and methods:
    - Attributes: `name` (String), `faction` (String), `strength` (int)
    - Methods: `transform()`, `speak(String message)`, `attack()`
2. Create two subclasses that inherit from `Transformer`:
    - `Autobot` class
    - `Decepticon` class
3. In each subclass, override the `attack()` method to provide a unique implementation.
4. Add a unique method to each subclass:
    - `Autobot`: Add a `protect()` method
    - `Decepticon`: Add a `deceive()` method
5. Create a class named `TransformerBattle` with a main method where you will:
    - Create instances of both `Autobot` and `Decepticon`
    - Demonstrate the use of inherited methods and overridden methods
    - Show how the unique methods of each subclass work

**Example Output**

```
Optimus Prime transforms into robot mode!
Optimus Prime says: Autobots, roll out!
Optimus Prime attacks with strength 95!
Optimus Prime protects the humans!

Megatron transforms into jet mode!
Megatron says: Decepticons, attack!
Megatron launches a devastating assault!
Megatron deceives the Autobots!
```

**Starter Code**

The `TransformerBattle.java` file contains the following starter code:

```java
package academy.javapro.lab;

class Transformer {
    // Add your attributes here

    // Add your constructor here

    // Add your methods here
}

class Autobot extends Transformer {
    // Add your constructor here

    // Override attack() method here

    // Add protect() method here
}

class Decepticon extends Transformer {
    // Add your constructor here

    // Override attack() method here

    // Add deceive() method here
}

public class TransformerBattle {
    public static void main(String[] args) {
        // Create instances of Autobot and Decepticon
        // Demonstrate inheritance and polymorphism here
    }
}

```

**Hints**

- Use the `super` keyword in the subclass constructors to call the superclass constructor.
- Remember to use the `@Override` annotation when overriding methods.
- Demonstrate polymorphism by using Transformer reference variables to hold Autobot and Decepticon objects.
- Use `instanceof` to check the type of a Transformer before calling subclass-specific methods.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required classes and methods
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.