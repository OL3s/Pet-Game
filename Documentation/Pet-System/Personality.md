[Back](Overview.md)

# Personality System

## Overview
The Personality System is designed to give each pet a unique set of personality traits that influence their behavior, interactions, and overall experience in the game. This system allows for diverse pet personalities, making each pet feel distinct and engaging for players.

## Personality Types
The personality system consists of various traits that can be assigned to pets. Each trait has a high and low value effect, which determines how the pet behaves in different situations.

| Personality   | Description                                                        | High Value Effect                              | Low Value Effect                                 |
|---------------|--------------------------------------------------------------------|------------------------------------------------|--------------------------------------------------|
| Friendly      | Enjoys interaction, responds positively to other pets.             | Seeks frequent interaction                     | Avoids social contact                            |
| Active        | High energy, requires frequent playtime and exercise.              | Needs lots of activity                         | Prefers calm, low-activity                       |
| Hunger        | Needs regular feeding, becomes unhappy if hungry for too long.     | Gets hungry quickly                            | Eats less frequently                             |
| Restless      | Needs rest, becomes unhappy if not allowed to sleep.               | Requires more sleep                            | Needs less sleep                                 |
| Affectionate  | Likes to be petted and cuddled, responds positively to affection.  | Seeks frequent affection                       | Prefers less physical contact                    |
| Curious       | Explores surroundings, enjoys discovering new things.              | Seeks new experiences                          | Content with routine                             |
| Social        | Enjoys being around other pets, becomes unhappy if isolated.       | High interaction increases happiness           | Prefers solitude                                 |
| Cleanliness   | Enjoys being clean, dislikes dirt or mess.                         | Seeks cleaning, avoids dirty areas             | Tolerates mess, dislikes being cleaned           |

## Implementation
The Personality System is implemented as a struct that holds the personality traits of a pet. Each trait can be adjusted based on the pet's interactions and experiences in the game.

```gml
// Default struct for pet personality, used to initialize a pet's personality traits.
personality = {
    friendly: 0.5,      // 0 to 1 scale
    playful: 0.5,       // 0 to 1 scale
    active: 0.5,        // 0 to 1 scale
    hunger: 0.5,        // 0 to 1 scale
    restless: 0.5,      // 0 to 1 scale
    affectionate: 0.5,  // 0 to 1 scale
    curious: 0.5,       // 0 to 1 scale
    social: 0.5         // 0 to 1 scale
};
```

## Personality Presets by Pet Type

Each pet type, including subtypes (e.g., `cat` → `black_cat`), comes with a preset range of personality trait values that reflect typical behaviors for that species or breed. For example, cats may generally be more independent and curious, while dogs might be more social and playful. Subtypes further refine these presets to capture breed-specific tendencies.

However, to ensure variety and uniqueness, each pet's actual personality is randomly generated within a defined "swing room" around these presets. This means that while most pets of a type will share common personality traits, there is always a chance for outliers—such as a particularly social cat or a reserved dog—making each pet feel distinct and occasionally surprising.

This approach balances consistency (so pets feel true to their type) with enough variability to keep gameplay interesting and unpredictable.
