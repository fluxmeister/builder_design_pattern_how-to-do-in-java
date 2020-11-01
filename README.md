<html>
builder_design_pattern_how-to-do-in-java
original source: <a href="https://howtodoinjava.com/design-patterns/creational/builder-pattern-in-java/" _target="blank">link</a>

The builder pattern, as name implies, is an alternative way to construct complex objects. This should be used only when you want to build different immutable objects using same object building process.

What is mentioned in GangOfFour “Design Patterns” book:
<i>The builder pattern is a design pattern that allows for the step-by-step creation of complex objects using the correct sequence of actions. The construction is controlled by a director object that only needs to know the type of object it is to create.</i>

And book gives example like below:

<img loading="lazy" src="img/Builder_UML_class_diagram.png" alt="Builder Pattern" width="500" height="171" class="aligncenter size-full wp-image-3862" srcset="https://howtodoinjava.com/wp-content/uploads/2014/05/Builder_UML_class_diagram.png 500w, https://howtodoinjava.com/wp-content/uploads/2014/05/Builder_UML_class_diagram-300x102.png 300w" sizes="(max-width: 500px) 100vw, 500px">

I really find it hard making use of above example in real life programming and applications. Above process is very much similar (not exactly) to Abstract factory pattern, where you find a factory (or builder) for a specific type of object, and then factory gives you a concrete instance of that object. The only big difference between this builder pattern and abstract factory pattern is that, builder provides you more control over the object creation process and that’s it. Apart from it, there are no major differences.

</html>