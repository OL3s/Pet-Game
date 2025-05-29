[Back](Overview.md)

# Stats System

The Stats System is responsible for managing the pet's stats, such as health, energy, hunger, and other needs. It provides methods to modify these stats and check their current values.

## Stats Variables

The stats variables represent the pet's current state and needs. Each stat is a value between 0 and 1. Theese are seperate from eachother, where functions are later used to get a combined value of the state like happiness or affection.

| Stat        | Description                                             |
|-------------|---------------------------------------------------------|
| Health      | Represents pet's well-being                             |
| Happiness   | Indicates how happy the pet is                          |
| Energy      | Indicates pet's stamina level                           |
| Hunger      | Shows how hungry the pet is                             |
| Cleanliness | How clean the pet is                                    |
| Social      | Measures how much social interaction the pet has        |
| Curiosity   | Reflects the pet's need for exploration and stimulation |
| Rest        | How well-rested the pet is                              |
| Bonding     | Tracks the strength of the pet's relationship with the player |

## Default Stats Struct
```gml
// Default struct for pet stats, used to initialize a pet's stats and has a value from 0 to 1.
stats = {
    health: 0.5,
    energy: 0.5,
    hunger: 0.5,
    happiness: 0.5,
    cleanliness: 0.5,
    social: 0.5,
    affection: 0.5,
    curiosity: 0.5,
    rest: 0.5,
    bonding: 0
};
```

## Stats Return Values
Functions that return stats values should return a value between 0 and 1, where:
- 0 means the stat is at its lowest
- 1 means the stat is at its highest

## Low Health Warning
When the pet's health drops below a certain threshold (e.g., 0.2), a warning should be displayed to the player, indicating that the pet needs immediate care.
When the health is too low, it needs to be handled by the player, such as taking the pet to a vet or providing medical care. The game should provide feedback on how to improve the pet's health.