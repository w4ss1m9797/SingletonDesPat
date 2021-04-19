The factory pattern is a creational pattern that provides a way to make objects without exposing creation logic. It involves two types:


The factory creates objects.
The products are the objects that are created.
Technically, there are multiple “flavors” of this pattern, including simple factory, abstract factory and others. However, each of these share a common goal: to isolate object creation logic within its own construct.

In this chapter, you’ll be adding onto the previous chapter’s project, Coffee Quest, to learn about a simple factory. It creates objects of a common type or protocol, and the factory’s type itself is known and used by consumers directly.

When should you use it?
Use the factory pattern whenever you want to separate out product creation logic, instead of having consumers create products directly.

A factory is very useful when you have a group of related products, such as polymorphic subclasses or several objects that implement the same protocol. For example, you can use a factory to inspect a network response and turn it into a concrete model subtype.

A factory is also useful when you have a single product type, but it requires dependencies or information to be provided to create it. For example, you can use a factory to create a “job applicant response” email: The factory can generate email details depending on whether the candidate was accepted, rejected or needs to be interviewed.

