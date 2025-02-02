# ZoneCommander
## Description
This game is a strategic game derived from the famous game S.T.A.L.K.E.R. 
Your goal is to take control of one of the factions in the Zone and as its leader, conquer the Zone.
However, achieving glory in the cruel Zone requires adaptation, strategic, political, and economical thinking.

## Game Definition

### Player Responsibility:
- **Define and update standardized equipment**
- **Highlight territories to capture and organize large-scale invasions**
- **Manage diplomatic connections with other factions**:
  - TODO: expand
- **Manage trades and supply chain**:
  - TODO: expand
- **Choose generals**

### AI Levels:
- **Faction Leader**:
  - Same responsibilities as the player.

- **Generals**:
  - Carry out invasions by orchestrating squads through their squad leaders, giving simpler commands to them.

- **Squad Leader**:
  - Carry out simpler commands by issuing direct orders to squad members.

- **Squad Member**:
  - Execute commands sent by the squad leader by breaking them down into atomic behaviors.

### Zone Events:
- **Mutant Migration**:
  - A relatively rare sight, but large numbers of mutants can migrate from one territory to another sometimes, posing significant threats to squads.
- **Blowout**:
  - Kills everything that didn't make it into a shelter and changes the places of anomalies. It also spawns new artifacts.
- **PSI Emission**:
  - Turns everyone who didn't make it to the shelter in time into Monolith members or Zombies. 
  - Those who were in Yantar or Radar regions will turn into Monolith members, everyone else will turn into Zombies.
- **Zombie Raids**:
  - A semi-organized event in which the Monolith faction sends large numbers of Zombies to strategic points or moving squads.
- **Zone Shortage**:
  - When many squads buy equipment, shortages can happen to specific items, such as combat gear, medicine, etc.

### Factions and Their Characteristics
TODO: do it based on this video https://youtu.be/kbOAj_MiWNU?si=tdVF2TY-iWEY5l5k
#### Duty:
- **Main Level Interests**: Rostok, Agroprom, Jupiter, Garbage
- **Main Base Level**: Rostok
- **Starting Values for Faction Relations**:
  - **Friends Towards**: Ecologist
  - **Neutral Towards**: Loner
  - **Hostile Towards**: Military, Mercenary, Freedom, Bandit, Clear Sky, Monolith, Renegade
- **Recruitment speed**: 
- **Special skill**: After all fights where Military members surrendered there is 25% chance 
that all the surrendered troops will join Duty.
- **Trading skills**: -1, due to only being able to sell artifacts to Ecologists
- **Equipment**:
  - **Type**: Soviet
  - **Tier**: High end

#### Freedom:
- **Main Level Interests**: Army Warehouses, Jupiter, Garbage
- **Main Base Level**: Army Warehouses
- **Starting Values for Faction Relations**:
  - **Friends Towards**: Loners
  - **Neutral Towards**: Bandits, Clear Sky
  - **Hostile Towards**: Duty, Military, Mercenaries, Monolith, Ecologists
- **Specialties**:
  - Advocates for free access to the Zone.
  - Trades artifacts freely with Loners and Bandits.
  - Prefers NATO weapons, often acquired through black-market routes.
  - Recruitment boost.

#### Ecologists:
- **Main Level Interests**: Yantar, Jupiter, Lake Yanov
- **Main Base Level**: Mobile scientific stations
- **Starting Values for Faction Relations**:
  - **Friends Towards**: Duty
  - **Neutral Towards**: Loners, Freedom
  - **Hostile Towards**: Bandits, Mercenaries, Monolith, Renegades
- **Specialties**:
  - Focused on researching anomalies, artifacts, and the Zone itself.
  - Relies on Duty and Military for protection.
  - Uses advanced scientific gear but limited in weapon variety.
  - Provides high-quality medical supplies and anomaly detectors.

#### Loners:
- **Main Level Interests**: Cordon, Garbage, Agroprom, Zaton
- **Main Base Level**: The Rookie Village (Cordon)
- **Starting Values for Faction Relations**:
  - **Friends Towards**: Freedom
  - **Neutral Towards**: Duty, Ecologists
  - **Hostile Towards**: Bandits, Mercenaries, Monolith, Renegades
- **Specialties**:
  - Jack-of-all-trades faction with flexible gear and no strict allegiances.
  - Trades artifacts and supplies freely across the Zone.
  - Grows its ranks organically as new stalkers enter the Zone.
  - Vulnerable due to lack of organized command structure.

#### Bandits:
- **Main Level Interests**: Dark Valley, Garbage, Limansk
- **Main Base Level**: Dark Valley
- **Starting Values for Faction Relations**:
  - **Friends Towards**: Mercenaries
  - **Neutral Towards**: Freedom
  - **Hostile Towards**: Duty, Ecologists, Loners, Monolith, Clear Sky
- **Specialties**:
  - Specializes in ambushes and extortion of artifacts and supplies.
  - Trades stolen goods and black-market artifacts.
  - Uses scavenged or stolen weaponry, with limited heavy gear.
  - High recruitment rates from ex-criminals and deserters.

#### Clear Sky:
- **Main Level Interests**: Swamps
- **Main Base Level**: Clear Sky base in the Swamps
- **Starting Values for Faction Relations**:
  - **Friends Towards**: Ecologists
  - **Neutral Towards**: Freedom, Loners
  - **Hostile Towards**: Bandits, Mercenaries, Duty, Monolith
- **Specialties**:
  - Focuses on deep research and maintaining the Zone’s balance.
  - Exclusively trades artifacts with Ecologists and selected allies.
  - Uses advanced experimental equipment, including anomaly detectors and armor.
  - Low recruitment due to its secretive and elite nature.

#### Monolith:
- **Main Level Interests**: Pripyat, CNPP, Red Forest
- **Main Base Level**: CNPP (Chernobyl Nuclear Power Plant)
- **Starting Values for Faction Relations**:
  - **Friends Towards**: None
  - **Neutral Towards**: None
  - **Hostile Towards**: Everyone
- **Specialties**:
  - Fanatical defenders of the Zone’s secrets.
  - Well-equipped with advanced weaponry and artifacts.
  - Recruitment is based on brainwashed stalkers and captured combatants.
  - Operates as a hivemind with coordinated and relentless strategies.

#### Mercenaries:
- **Main Level Interests**: Limansk, Zaton, Jupiter
- **Main Base Level**: Scattered camps, primarily in Limansk
- **Starting Values for Faction Relations**:
  - **Friends Towards**: Bandits
  - **Neutral Towards**: Freedom
  - **Hostile Towards**: Duty, Loners, Ecologists, Monolith
- **Specialties**:
  - Hired guns available for the highest bidder.
  - Trades artifacts and supplies exclusively for profit.
  - Highly trained but fewer in number due to elite requirements.
  - Uses a mix of NATO and Soviet equipment, depending on their employer.

#### Renegades:
- **Main Level Interests**: Swamps
- **Main Base Level**: Scattered camps in the Swamps
- **Starting Values for Faction Relations**:
  - **Friends Towards**: None
  - **Neutral Towards**: Bandits
  - **Hostile Towards**: Duty, Freedom, Ecologists, Loners, Monolith
- **Specialties**:
  - Loosely organized bandits with a focus on chaos and territory control.
  - Poorly equipped but highly mobile.
  - Recruits deserters and failed stalkers.
  - Weak overall due to lack of discipline and resources.

#### Military:
- **Main Level Interests**: Cordon, Agroprom, Outskirts of Pripyat
- **Main Base Level**: Military outposts (Cordon, Agroprom Underground)
- **Starting Values for Faction Relations**:
  - **Friends Towards**: None
  - **Neutral Towards**: Ecologists
  - **Hostile Towards**: Everyone else
- **Specialties**:
  - Operates as the Zone’s enforcers, aiming to suppress illegal activities.
  - Uses well-organized military tactics and heavy Soviet gear.
  - Recruitment is limited to trained soldiers.
  - Rigid chain of command and structured operations.

## Project Structure
```plaintext
squad_strategy_game/
├── game/                       # Core game logic and domain layer
│   ├── __init__.py             # Makes this a package
│   ├── game_loop.py            # Main game loop
│   ├── world.py                # World and map-related logic
│   ├── squad.py                # Squad mechanics and attributes
│   ├── faction.py              # Faction-related logic
│   ├── location.py             # Location logic and attributes
│   ├── events.py               # Event system (e.g., battles, encounters)
│   ├── actions.py              # Player and AI actions
│   └── ai/                     # AI behavior
│       ├── __init__.py
│       ├── decision_maker.py   # Faction or squad AI logic
│       └── strategy.py         # High-level AI strategy
├── ui/                         # User interface
│   ├── __init__.py
│   ├── terminal_ui.py          # Terminal-based interface
│   └── graphical_ui.py         # Future graphical interface
├── data/                       # Persistence layer
│   ├── __init__.py
│   ├── save_manager.py         # Save and load game data
│   ├── database.py             # Handles persistent storage (e.g., SQLite)
│   └── fixtures/               # Predefined data (e.g., maps, factions)
│       ├── __init__.py
│       ├── maps.json           # Example map data
│       └── factions.json       # Example faction data
├── config/                     # Configuration files
│   ├── __init__.py
│   ├── settings.py             # Game settings (e.g., difficulty, graphics)
│   └── logger.py               # Logging configuration
├── tests/                      # Unit and integration tests
│   ├── __init__.py
│   ├── test_game_loop.py       # Tests for the game loop
│   ├── test_squad.py           # Tests for squad mechanics
│   ├── test_ai.py              # Tests for AI behaviors
│   └── test_ui.py              # Tests for UI components
├── assets/                     # Game assets (graphics, sound, etc.)
│   ├── sprites/                # Placeholder for 2D assets
│   └── audio/                  # Placeholder for sound assets
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
├── .gitignore                  # Git ignore file
└── main.py                     # Entry point to the game
```

