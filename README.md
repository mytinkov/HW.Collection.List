# Collection-1
Project with a chessboard and a racing application. Implementation of Collections

1. Racing Application: A list of all the cars participating in the race has been created. The race includes objects from all classes: 'Passenger Cars,' 'Trucks,' and 'Buses.' Each car has a list of sponsors and a driver. A driver can only manage one car in the race and no more. One sponsor can support multiple cars. A sponsor can be either a company or an individual. As sponsor parameters, it contains a name (or company name) and the amount of support. Sponsors have a 'sponsor a race' method. In addition, each car undergoes maintenance, so it has a team of mechanics.

A new mechanic class has been created with parameters: first name and last name, the company they work for, and the types of cars they can work with (for example, only passenger cars, trucks, buses, or all). Methods include 'perform maintenance' and 'repair a car.' The number of mechanics who can work on one car is fixed. One mechanic can work with multiple cars. A program has been implemented to find out the driver's name, sponsors, and mechanics for each car.

A 'Service Station' class has been added, which implements a queue of cars. In addition, the class has methods to 'add a car to the queue' and 'perform a technical inspection of a car.' Buses do not need maintenance before the race, so they do not join the queue. Each new car object enters the end of the maintenance queue. As soon as a car undergoes maintenance, it should be removed from the queue.

2. Project with console output of a chessboard. Working with a nested (two-dimensional) list. Two-dimensional list: List<List> biDemArrList = new ArrayList<>();