Download Link: https://assignmentchef.com/product/solved-comp2396-assignment-2-understanding-of-basic-inheritance-in-java
<br>
Assignment 2

Introduction

This assignment tests your understanding of basic inheritance in Java.

You are asked to write a number of Java classes to model basic shapes: Shape, Rectangle, Square and Diamond. Rectangle and Diamond are the subclasses of Shape, and Square is the subclass of Rectangle

You are also required to write JavaDoc for all non-private classes and non-private class members.

Implementation

The Shape class:Methods Shape()Constructor, create an empty shape. A shape is typically a 2D array of pixels (boolean values).String toString()Return a drawing of the shape as a String. Each pixel should be represented by the character * and each empty space should be represented by the space character. Newlines are represented by newline character 
.int getArea()Return the area, i.e., the number of pixels in the shape.Shape intersect(Shape s)Return a new Shape object representing the intersection of this Shape object and s.Shape union(Shape s)Return a new Shape object representing the union of this Shape object and s.

The Rectangle class, a subclass of the Shape class:MethodsRectangle(int width, int height)Constructor, create a rectangle with the specific width and height. For example, if width = 5 and height = 3, a drawing of this shape will look like this:

The Diamond class, a subclass of the Shape class:MethodsDiamond(int size)Constructor, create a diamond shape with the specific size. For example, if size = 3, a drawing of this shape will look like this (the empty area is represented by space characters and each newline is represented by the newline character 
.):

The Square class, a subclass of the Rectangle class:MethodsSquare(int size)Constructor, create a square with the specific size. For example, if size = 3, a drawing of this shape will look like this:****** ***