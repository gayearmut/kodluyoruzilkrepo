## Zoo Uml Class
- You design a system to track information about animals in a zoo.

```
Animals:
-Horses (horses, zebras, donkeys, etc.),
-Felines (tigers, lions, etc.),
-Rodents It is characterized by species in groups such as rodents (rats, beavers, etc.).

- Most of the information stored about animals is the same for all groupings.
species name, weight, age, etc.
- The system should also be able to get the dosage of specific drugs for each animal => getDosage()
- System should be able to calculate Feed times => getFeedSchedule()
- The logic for the system to perform these functions will be different for each grouping. For example, the feeding algorithm will be different for horses and different for tigers.

Using the polymorphism model, design a class diagram to handle the situation described above.
```
## Airport Company Management System 
- Design a system for the management of flights and pilots.
```
- Airlines operate the flights. Every airline has an identity.
- The airline has different types of aircraft.
- Aircraft may be in operation or in a state of repair.
- Each flight has a unique identity, airport to take off and land at, and departure and landing times.
- Every flight has a pilot and co-pilot, and they operate the plane.
- Airports have unique IDs and names.
- Airlines have pilots, and each pilot has a level of experience.
- An aircraft type may need a certain number of pilots.
Draw the Class diagram describing this system.
```
