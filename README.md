# Inheritance-And-Composition
Building a car with inheritance or composition.
## PCPP1 - Lab
* # IMPORTANT
To favor composition over inheritance is a design principle that gives
the design higher flexibility, as you can choose which domain-specific
objects should be incorporated into your ultimate object. It's like
arming your base machine with tooling, dedicated to running a specific
task, but not building a wide hierarchy structure of classes covering
all possible hardware combinations.

In fact, with the composition approach you can more easily respond
to the requirement changes regarding classes, as it does not require
deep dependency investigations which you would spot while implementing
code with the inheritance approach.


On the other hand, there is a clear drawback: composition transfers
additional responsibilities to the developer. The developer should
assure that all component classes that are used to build the composite
should implement the methods named in the same manner to provide
a common interface.

In the case of inheritance, if the developer forgets to implement
a specific method, the inherited method with the same name will be
called. Additionally, in the case of inheritance, the developer has
to re-implement only the specific methods, not all of them, to gain
a common interface.
