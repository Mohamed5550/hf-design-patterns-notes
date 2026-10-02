# Chapter 1: Welcome to Design Patterns

## Someone has already solved your problem

- The best way to learn use patterns is to load your brain with them and find ways in your existing code to apply them
- Instead of code resue, with patterns you get experience resue

## It all started with a simple SimUDuck app

- A simple duck super class
- Duck types inherit from this class

## Wee need the duck to fly

- We simply add a fly method in the superclass
- But there is a hirrible problem, not all duck can fly


## Inheritance is not the answer

- Interface fit better in this case
- But wait, what if we want to change the fly behavior in all 48 of flying duck subclasses?

## An important design principle

- Separate what varies from what doesn't
- This principle forms the basis for almost every design pattern

## The second design principle

- Program to an interface, not an implementation


## A better design for the duck problem

- We create interafaces and make a class for each bahvoir that implement the interfaces, outside the duck subclasses

## HAS-A can be better than IS-A
- What we have used so far is called the strategy pattern

## The strategy pattern

- Define a familty of algorithms, encapsulate them, make then interchangeable, it's independent from the clients that use it

## Shared Vocabulary

- Design patterns give you a shared vocalbulary to communicate with other developers