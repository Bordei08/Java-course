
# Laboratorul 4

 * [Compulsory](#Compulsory) :heavy_check_mark:
 * [Homewrok](#homework) :heavy_check_mark:
 * [Bonus](#bonus) :heavy_check_mark:

## Enunt

Use appropriate collections in order to represent data (otherwise: -0.5 points)

Use Java Stream API in order to perform aggregate operations on data.

A city hall wants to install surveillance cameras at all intersections in a city.
To do this, it must connect all intersections with data cables, along the streets between them, such that the resulting network is connected.
We assume that the lengths (in km) of the streets between all the intersections of the city are known and the costs of installing the cables is proportional with the street lengths.
The problem is to determine how to install the data cables (on which streets) such as the total cost is minimum.

Example (the dots are the intersections, the lines are the streets)


![image](https://user-images.githubusercontent.com/79217056/159515649-fc094ee7-7e0f-4b22-8508-c3e7d89b82fc.png)

## Compulsory 

Este implementat in Homework, dar nu este trimis la timp :disappointed_relieved:

### Enunt!
 * Create a Maven project. :heavy_check_mark:
 * Create an object-oriented model of the problem. Streets have names and lengths, intersections have names. A street joins two intersections. :heavy_check_mark:
 * Create the streets and the intersections of the problem described in the example. Use streams in order to easily create the intersections. :heavy_check_mark:
 * Create a list of streets, using LinkedList implementation and sort it by the length, using a comparator expressed as a lambda-expression or method reference. Make sure all the objects are comparable. :heavy_check_mark:
 * Create a set of intersections, using a HashSet implementation. Verify the property that a Set does not contain duplicates.:heavy_check_mark:

## Homework

### Enunt
  * Create a class that describes the city. :heavy_check_mark:
  * Using Java Stream API, write a query that display all the streets that are longer than a specified value and join at least 3 streets. :heavy_check_mark:
  * Use a third-party library in order to generate random fake names for intersections and streets.  :heavy_check_mark:
  * You may use this package of JGraphT in order to solve the problem (or other library). :heavy_check_mark:
  * A personal implementation of the algorithm will be will be scored extra (+1p). :heavy_check_mark:

![image](https://user-images.githubusercontent.com/79217056/159517954-e4329273-0b50-4bf1-a87f-ed690252697b.png)

## Bonus 

Varianta propusa nu implementeaza problema TSP ci face o parcurgere pe MST, compexitatea find  O(m log(n) + mn).

### Enunt

The city hall wants to regularly inspect the surveillance cameras, sending a maintenance car to go through it all.

 * Implement an algorithm that determines the route of the maintenance car, in order to minimize the total length. The algorithm must run fast and should not find a solution that is twice as bad than the optimum route. :heavy_check_mark:
 * Create a random problem generator, making sure that the lengths between intersections satisfy the triangle inequality. :heavy_check_mark:


Costul pentru exemplul din laborator.
![image](https://user-images.githubusercontent.com/79217056/159949969-930660cf-455a-4bc8-ae11-2c461094f7bd.png)


Costul pentru o instanta random cu 100 de noduri si 200 de muchi

![image](https://user-images.githubusercontent.com/79217056/159950289-0b85726c-c139-4d66-ac40-988814f70a60.png)

