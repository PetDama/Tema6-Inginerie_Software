<h1>Research about Adapter, Bridge and Proxy Patterns</h1>
1. Adapter Pattern:

The Adapter pattern is a structural pattern that allows two incompatible interfaces to work together. It acts as an intermediary ("adapter") between two components that cannot communicate directly.

Use Case: This pattern is useful when you have an old component or interface and you want to use it in a new context that requires a different interface. The adapter converts requests received from the new interface into a format understood by the old component.
<hr>
2. Bridge Pattern:

Description: The Bridge pattern is another structural pattern that separates the abstraction of an entity from its implementation. It allows these two aspects to evolve independently of each other.

Use Case: This pattern is useful when you have a set of entities (e.g., geometric shapes) and different ways to implement them (e.g., rendering methods). With the Bridge pattern, you can connect any shape to any rendering method, allowing them to vary independently.
<hr>
3. Proxy Pattern:

Description: The Proxy pattern is a structural pattern that provides a substitute for another object to control access to it. This can be done to add additional functionalities, such as access control or handling costly objects.

Use Case: The Proxy pattern is useful when you want to control access to an object or add additional functionalities before or after calling the methods of the real object. It can also be used to implement logging, lazy loading, or security control.
