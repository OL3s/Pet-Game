# Wireframes Scenes

## Home Scene
<details>
<summary>Default View</summary>

```
┌─────────────────────────────────────┐
│ Coins: 150             ┌───┐ ┌───┐  │ <- Status bar
│                        │🔔2│ │ ≡ │  │
│                        └───┘ └───┘  │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│                                     │
│           ┌───────────┐             │
│           │   Map     │             │ <- Navigation button
│           └───────────┘             │
└─────────────────────────────────────┘
```

</details>

<details>
<summary>Notifications Panel</summary>

```
┌──────────────────────────────────────┐
│ Coins: 150             ┌───┐ ┌───┐   │ <- Status bar
│                        │🔔2│ │ ≡ │   │
│                        └───┘ └───┘   │
│ ┌───────────────────────────────┐    │
│ │      Notifications            │    │ <- Notifications panel
│ │ ────────────────────────────  │    │
│ │ • Fluffy is hungry!           │    │
│ │ • Daily reward available!     │    │
│ │ • New furniture in store!     │    │
│ │                               │    │
│ │ [Clear All]                   │    │
│ └───────────────────────────────┘    │
│                                      │
│                                      │
│                                      │
│                                      │
│                                      │
│                                      │
│                                      │
│           ┌───────────┐              │
│           │   Map     │              │ <- Navigation button
│           └───────────┘              │
└──────────────────────────────────────┘
```

</details>

<details>
<summary>Pet Selected</summary>

```
┌─────────────────────────────────────┐
│ Coins: 150             ┌───┐ ┌───┐  │ <- Status bar
│                        │🔔2│ │ X │  │ <- Notifications and close buttons
│                        └───┘ └───┘  │
│                                     │
│    ┌─────────────────────────────┐  │
│    │   Fluffy - 😊 Happy         │  │ <- Pet name and mood
│    └─────────────────────────────┘  │
│                                     │
│        ┌─────────────────────┐      │
│        │                     │      │
│        │   Fluffy (pet art)  │      │ <- Large pet display
│        │                     │      │
│        └─────────────────────┘      │
│                                     │
│   "Fluffy seems ready to play!"     │ <- Pet response/message
│                                     │
│ ┌─────┐ ┌─────┐ ┌─────┐ ┌──────┐    │
│ │ Pet │ │Bathe│ │ Vet │ │Hotel │    │ <- Interaction buttons
│ └─────┘ └─────┘ └─────┘ └──────┘    │
│                                     │
│ ┌───────────────────────────────┐   │
│ │ Bond Level: ★★★☆☆           │   │ <- Bond level
│ └───────────────────────────────┘   │
│                                     │
│ ┌───────────────────────────────┐   │
│ │ ❤️ 80%  🍽️ 60%  😀 85%  🧼 55%│ │ <- Stats
│ └───────────────────────────────┘   │
│                                     │
└─────────────────────────────────────┘
```

</details>

### Hamburger Menu

### Hamburger - Toys

### Hamburger - Snacks

### Hamburger - Food

### Hamburger - Furniture

### Hamburger - Settings

## Hotel Scene

<details>
<summary>Default View</summary>

```
┌─────────────────────────────────────┐
│ Coins: 99               ┌───┐       │
│                         │🔔2│       │ <- Notifications button only
│                         └───┘       │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ Pets Currently at Hotel:        │ │
│ │ ☑ Fluffy - 2 days (100 coins)   │ │ <- Scrollable list of pets
│ │ ☑ Max    - 1 day  (50 coins)    │ │    with checkboxes and
│ │ ☐ Bella  - 3 days (150 coins)   │ │    stay duration/cost
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ Total Cost: 150 coins           │ │ <- Total cost for selected
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │        Check Out Pets           │ │ <- Check out button
│ └─────────────────────────────────┘ │
│                                     │
│           ┌───────────┐             │
│           │   Map     │             │ <- Navigation button
│           └───────────┘             │
└─────────────────────────────────────┘
```

</details>

## Vet Scene

<details>
<summary>Default View</summary>

```
┌─────────────────────────────────────┐
│ Coins: 99               ┌───┐       │
│                         │🔔2│       │ <- Notifications button only
│                         └───┘       │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │     Pets Currently at Vet       │ │ <- Title/header
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ ● Fluffy - 2 days (100 coins)   │ │
│ │   ❤️ 60%  | Status: 🤒 Sick     │ │ <- Health and status
│ │ ○ Max    - 1 day  (50 coins)    │ │
│ │   ❤️ 80%  | Status: 💤 Resting  │ │
│ └─────────────────────────────────┘ │
│                                     │
│ Select pets to check out:           │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ Total Cost: 100 coins           │ │ <- Total cost for selected
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │      Check Out Selected Pets    │ │ <- Confirmation button
│ └─────────────────────────────────┘ │
└─────────────────────────────────────┘
```

</details>

## Store Scene

<details>
<summary>Default View</summary>

```
┌─────────────────────────────────────┐
│ Coins: 99               ┌───┐       │
│                         │🔔2│       │ <- Notifications button only
│                         └───┘       │
│ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────────┐ │ <- Category tabs
│ │Food │ │Toys │ │Items│ │Furniture│ │
│ └─────┘ └─────┘ └─────┘ └─────────┘ │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ ┌────┐  ┌────┐  ┌────┐  ┌────┐  │ │
│ │ │Item│  │Item│  │Item│  │Item│  │ │
│ │ │ 1  │  │ 2  │  │ 3  │  │ 4  │  │ │ <- Scrollable grid 
│ │ │$20 │  │$35 │  │$15 │  │$40 │  │ │    of store items
│ │ └────┘  └────┘  └────┘  └────┘  │ │
│ │                                 │ │
│ │ ┌────┐  ┌────┐  ┌────┐  ┌────┐  │ │
│ │ │Item│  │Item│  │Item│  │Item│  │ │
│ │ │ 5  │  │ 6  │  │ 7  │  │ 8  │  │ │
│ │ │$25 │  │$30 │  │$50 │  │$45 │  │ │
│ │ └────┘  └────┘  └────┘  └────┘  │ │
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ Premium Food - $45              │ │
│ │ +30% Hunger, +10% Happiness     │ │ <- Selected item details
│ │ "Your pet will love this treat!"│ │
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────┐ ┌─────────────┐ │
│ │   Buy (45 coins)│ │   Count: 2  │ │ <- Action button
│ └─────────────────┘ └─────────────┘ │
└─────────────────────────────────────┘
```

</details>

## Map Scene
<details>
<summary>Default View</summary>
```
┌─────────────────────────────────────┐
│ ┌───────┐               ┌───┐ ┌───┐ │ <- Back & settings buttons
│ │ Back  │               │ $ │ │ ≡ │ │
│ └───────┘               └───┘ └───┘ │
│                                     │
│     ┌─────────────────────────┐     │
│     │       ┌───────┐         │     │
│     │       │ Store │         │     │
│     │       └───────┘         │     │
│     │                         │     │
│     │  ┌────┐         ┌────┐  │     │ <- Interactive map with
│     │  │Home│         │Vet │  │     │    location markers
│     │  └────┘         └────┘  │     │
│     │                         │     │
│     │         ┌───────┐       │     │
│     │         │ Hotel │       │     │
│     │         └───────┘       │     │
│     └─────────────────────────┘     │
│                                     │
│         Tap a location to view      │
│         details and travel options  │
│                                     │
└─────────────────────────────────────┘
```
</details>

<details>
<summary>Selected Location View (Collapsed)</summary>

```
┌─────────────────────────────────────┐
│ ┌───────┐               ┌───┐ ┌───┐ │ <- Back & settings buttons
│ │ Back  │               │ $ │ │ ≡ │ │
│ └───────┘               └───┘ └───┘ │
│                                     │
│     ┌─────────────────────────┐     │
│     │       ┌───────┐         │     │
│     │       │ Store │         │     │
│     │       └───────┘         │     │
│     │                         │     │
│     │  ┌────┐         ┌────┐  │     │ <- Interactive map with
│     │  │Home│         │Vet │  │     │    location markers
│     │  └────┘         └────┘  │     │
│     │                         │     │
│     │         ┌───────┐       │     │
│     │         │ Hotel │       │     │
│     │         └───────┘       │     │
│     └─────────────────────────┘     │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │           Vet Clinic            │ │ <- Selected location info
│ │ Treat your sick pets here       │ │
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────┐ ┌─────────────┐ │
│ │      Go Here    │ │ Fast Travel │ │ <- Navigation actions
│ └─────────────────┘ └─────────────┘ │
└─────────────────────────────────────┘
```

</details>


## Home Scene - Pet Bathing
```
┌─────────────────────────────────────┐
│ Coins: 99               ┌───┐       │
│                         │🔔2│       │ 
│                         └───┘       │
│ ┌─────────────────────────────────┐ │
│ │    Fluffy - Bath Time 🛁        │ │ <- Pet name and activity
│ └─────────────────────────────────┘ │
│                                     │
│     ┌─────────────────────────┐     │
│     │                         │     │
│     │                         │     │
│     │      Pet in Bath        │     │ <- Pet in bathtub display
│     │                         │     │
│     │                         │     │
│     └─────────────────────────┘     │
│                                     │
│ "Splash! Fluffy seems to enjoy it!" │ <- Pet response message
│                                     │
│ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐     │
│ │Brush│ │ Soap│ │Rinse│ │ Dry │     │ <- Bath interaction buttons
│ └─────┘ └─────┘ └─────┘ └─────┘     │    (from Interact.md)
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ Cleanliness: █████████░░ (80%)  │ │ <- Cleanliness progress
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │         Finish Bath             │ │ <- Finish button
│ └─────────────────────────────────┘ │
└─────────────────────────────────────┘
```

## Home Scene - Closeup
```
┌─────────────────────────────────────┐
│ Coins: 150             ┌───┐        │ <- Status bar
│                        │🔔2│        │
│                        └───┘        │
│                                     │
│    ┌─────────────────────────────┐  │
│    │   Fluffy - 😊 Happy         │  │ <- Pet name and mood
│    └─────────────────────────────┘  │
│                                     │
│        ┌─────────────────────┐      │
│        │                     │      │
│        │   Fluffy (closeup)  │      │ <- Large closeup pet art
│        │                     │      │
│        └─────────────────────┘      │
│                                     │
│   "Fluffy looks at you closely!"    │ <- Closeup message
│                                     │
│           ┌───────┐ ┌───────┐       │
│           │Snack  │ │Brush  │       │ <- Interaction buttons
│           └───────┘ └───────┘       │
│                                     │
│           ┌────────────────┐         │
│           │ Finish Interact│         │ <- Finish/confirm interaction button
│           └────────────────┘         │
└─────────────────────────────────────┘
```