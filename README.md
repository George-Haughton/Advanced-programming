# Advanced-programming
This is a UML diagram I made within draw.io about the Factory design pattern. This UML diagram shows The product designing the interface for objects that the factory method will create. It shows the ConcreteProduct produces/implements the Product interface. The Creator defining the method FactoryMethod which will then return a Product Object; and lastly it shows the ConcreteCreator overriding the generating method that created COncreteProduct objects.

![alt text](https://gyazo.com/b35f21b618df11bf9fe0bd40e932ffee.png)


This is another UML diagram I made with draw.io about the Adapt design pattern. This UML diagram shows the Target defining the domain-specific interface that the client will use. The Adapter adpats the interface Adaptee to the target interface. It shows the Adaptee defining an existing interface that needs adapting and finally the client collaborating with objects conforming to the target audience.

![alt text](https://gyazo.com/54551222b631a9ed4c5dd974ff6aa9bb.png)

This final UML diagram I also made within draw.io and it is about the Observer design pattern. It shows the Observable defining the operations for attaching and detaching observers from the client. How the ConcreteObservable maintains the state of the object and when a change in state happens it lets the attached Observers know. Also it shows how the Observer defines the operations used when notifying the object; and finally shows the implementations of the concrete Observer.
