# **Game Design Document (GDD) - ZoneCommander**

## **1. Game Overview**
### **Game Title:**
**ZoneCommander**

### **Genre:**
Strategic, Real-Time, Tactical Management

### **Inspiration:**
Derived from the **S.T.A.L.K.E.R.** universe, ZoneCommander immerses players in the dangerous and unpredictable Zone. The player takes control of one of the factions in the Zone and must **conquer** and **dominate** by mastering diplomacy, military strategy, and economic planning.

### **Core Gameplay Concept:**
Players assume the role of a **Faction Leader**, commanding their chosen faction’s operations across the Zone. They must balance **expansion, diplomacy, combat, economy, and survival**, while also navigating **randomized Zone events** that influence the game world. Additionally, they must reach their faction's goal, that is derived from the faction's values and view over the Zone. 

## **2. Player Role & Responsibilities**
As a **Faction Leader**, the player must:
- **Define and update standardized equipment** for their squads.
- **Highlight territories to capture** and organize **large-scale invasions**.
- **Manage diplomatic relations** with other factions.
- **Oversee trade and supply chains**.
- **Appoint and command generals** to lead the faction’s operations.

## **3. AI Hierarchy & Responsibilities**
### **Faction Leader AI (AI-Driven Factions)**
- Competes against the player with similar faction management mechanics.

### **General AI**
- Executes large-scale invasions, deploying squads through their leaders.

### **Squad Leader AI**
- Manages small-scale operations and directs squad members.

### **Squad Member AI**
- Executes specific tasks based on squad leader’s orders.

## **4. Zone Events**
The **Zone is dynamic** and will introduce challenges to both **players and AI factions** through the following **events**:

### **Mutant Migration**
- Large numbers of mutants migrate unpredictably, threatening squads in certain regions.

### **Blowout**
- A catastrophic event that **wipes out everything outside a shelter**, shifts anomalies, and spawns new artifacts.

### **PSI Emission**
- A psychic wave turns all unprotected individuals into **Monolith members** or **Zombies**, based on location.

### **Zombie Raids**
- The Monolith faction orchestrates **coordinated zombie attacks** against strategic locations.

### **Zone Shortage**
- Shortages occur when factions over-purchase specific items, affecting gear, medicine, and supplies.

## **5. Factions & Characteristics**
Each faction has **unique play styles, relationships, and bonuses**.

Characteristics specification: 
Main Interest: Possible main base of a faction, which the faction leader chooses. (Refer to possible locations)
Alliances: Defines the base relations in between factions. (Friendly/Neutral/Hostile)
Recruitment speed: Determines how many new troops the faction leader can spawn per day. (troops/day)
Weapon system: Determines the weapon system the faction uses. (NATO/Warsaw pact)
Armor type: Determines the aim of the armors. (Environmental protection/Combat protection)
Trading skills: Determines the faction's ability to sell artifacts and buy gear. (number of trade partners)

TODO: Continue this


### **Duty**
- **Main Interests:** Rostok, Agroprom, Jupiter, Garbage.
- **Alliances:** Friends with Ecologists, Neutral to Loners, Hostile to Military, Mercenaries, Freedom, Bandits, Clear Sky, Monolith, and Renegades.
- **Recruitment Speed:** Medium.
- **Special Ability:** **25% chance to recruit surrendered Military troops.**
- **Trading Skills:** Poor (-1) due to only selling artifacts to Ecologists.
- **Equipment Type:** Soviet mid/high tier weapons, more combat oriented armors.

### **Freedom**
- **Main Interests:** Army Warehouses, Jupiter, Garbage.
- **Alliances:** Friends with Loners, Neutral to Bandits and Clear Sky, Hostile to Duty, Military, Mercenaries, Monolith, and Ecologists.
- **Recruitment Speed:** High.
- **Specialty:** Increased recruitment speed.
- **Trading:** Free trade of artifacts with Loners and Bandits.
- **Equipment:** Low and mid tier NATO weapons, perfectly balanced environmental protection and combat armors.

### **Ecologists**
- **Main Interests:** Yantar, Jupiter, Lake Yanov.
- **Alliances:** Friends with Duty, Neutral to Loners and Freedom, Hostile to Bandits, Mercenaries, Monolith, and Renegades.
- **Specialty:** Advanced **scientific research and anomaly study.**
- **Equipment:** Low tier NATO weapons, high environmental protection but low combat efficiency armors.

### **Loners**
- **Main Interests:** Cordon, Garbage, Agroprom, Zaton.
- **Alliances:** Friends with Freedom, Neutral to Duty and Ecologists, Hostile to Bandits, Mercenaries, Monolith, and Renegades.
- **Specialty:** Versatile playstyle with **organic faction growth.**
- **Weakness:** Lacks a **centralized command structure.**
- **Equipment:** 

### **Bandits**
- **Main Interests:** Dark Valley, Garbage, Limansk.
- **Alliances:** Friends with Mercenaries, Neutral to Freedom, Hostile to Duty, Ecologists, Loners, Monolith, and Clear Sky.
- **Specialty:** **Ambush tactics and artifact extortion.**
- **Weakness:** **Poor access to heavy equipment.**

### **Clear Sky**
- **Main Interests:** Swamps.
- **Alliances:** Friends with Ecologists, Neutral to Freedom and Loners, Hostile to Bandits, Mercenaries, Duty, and Monolith.
- **Specialty:** **Elite but small-scale faction with experimental tech.**
- **Weakness:** **Low recruitment rate.**

### **Monolith**
- **Main Interests:** Pripyat, CNPP, Red Forest.
- **Alliances:** None, **hostile to all.**
- **Specialty:** **Highly disciplined, well-equipped, hive-mind tactics.**
- **Weakness:** **No external recruitment.**

### **Mercenaries**
- **Main Interests:** Limansk, Zaton, Jupiter.
- **Alliances:** Friends with Bandits, Neutral to Freedom, Hostile to Duty, Loners, Ecologists, and Monolith.
- **Specialty:** **Elite tactical units for hire.**
- **Weakness:** **Small numbers due to high skill requirements.**

### **Renegades**
- **Main Interests:** Swamps.
- **Alliances:** None, **neutral to Bandits, hostile to all others.**
- **Specialty:** **High mobility and adaptability.**
- **Weakness:** **Weak structure and poor discipline.**

### **Military**
- **Main Interests:** Cordon, Agroprom, Outskirts of Pripyat.
- **Alliances:** Neutral to Ecologists, **hostile to all other factions.**
- **Specialty:** **Strict command structure and heavy firepower.**
- **Weakness:** **Limited to trained soldiers (slow recruitment).**

## **6. Gameplay Systems (To be Expanded)**
- **Diplomacy and Faction Relations** (TBD)
- **Trading & Economy** (TBD)
- **Resource Management** (TBD)
- **Combat System & Tactics** (TBD)
- **Squad Management & Customization** (TBD)

## **7. Future Development**
- **Graphical UI enhancement**
- **Expanded AI Behavior & Diplomacy**
- **Dynamic Mission Generator**
- **Multiplayer Mechanics** (potentially cooperative faction play)