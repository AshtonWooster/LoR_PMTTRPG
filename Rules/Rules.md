# Project Moon Tabletop Roleplaying Game - LoR Styled

![Logo](../Images/GarethCircle.png)

## Index
- [**Act 1: Introduction**](#act-1-introduction)
- [**Act 2: Characters**](#act-2-characters)
- [**Act 3: Pages**](#act-3-pages)
- [**Act 4: Equipment**](#act-4-equipment)
- [**Act 5: Creating a Character**](#act-5-creating-a-character)
- [**Act 6: Deckbuilding**](#act-6-deckbuilding)
- [**Act 7: Core Systems**](#act-7-core-systems)
- [**Act 8: Combat**](#act-8-combat)
- [**Act 9: Economy**](#act-9-economy)
- [**Credits**](#credits)

## Act 1: Introduction

## Act 2: Characters

### Resources
> Charcters maintain various **Resources** as a means to interact with their environment. Actions and stimuli can affect a character's Resources. 

#### Health
> **Health** is a resource depleted by taking Damage and recovered through Health Recovery. When a character's Health is reduced to 0, they are **Knocked Out**. 

Health Formula: `64 + (10-Rank)*16 + Fortitude*10`

#### Stagger Resist
> **Stagger Resist** is a resource depleted by taking Stagger Damage and recovered through Stagger Recovery. When a character's Stagger is reduced to 0, they are **Staggered**.

Stagger Resist Formula: `20 + (10-Rank)*2 + Temperance*4`

#### Light
> **Light** is a resource depleted by using **Pages**, **Effects**, or **Passives** that consume Light and recovered through Light Recovery.

Light Formula: `3 + ((10-Rank)/2 Rounded Down)`

#### Sanity
> **Sanity** is a resource depleted by taking Sanity Damage and recovered through Sanity Recovery. A character's minimum Sanity is the negative of their maximum value. So, a character with a max Sanity of 15 will panic at -15. When a character's Sanity is reduced to their minimum, they enter **Panic**.

Sanity Formula: `15 + (10-Rank) + Prudence*2`

### Rank
> **Rank** is determined by a character's **Fixer Grade**, **Syndicate Grade**, or equivalent determined by the Game Master. Rank affects a character's Resources' maximums. The GM decides when players are able to rank up their characters, typically after a large achievement. The GM can also require characters to perform an action to increase rank, such as taking a fixer exam or equivalent.

### Stats
> **Stats** are determined by a character's Rank, and can be increased or decreased by other means such as **Equipment** or **Passives**. Stats affect everything from Resources, **Dice Rolls**, and more as determined by the Game Master. When choosing **Proficiencies**, a certain minimum of **Primary** and/or **Secondary Stats**, specific to the desired Proficiency, must be met.

#### Primary Stats
> A character's **Primary Stats** determine their base Resources and Speed. These are increased by investing **Primary Stat Points** on ranking up.

- **Fortitude**
    > A character's max Health is increased by their **Fortitude**.
    
    Health Formula: `64 + (10-Rank)*16 + Fortitude*10`

- **Prudence**
    > A character's max Sanity is increased by their **Prudence**.

    Sanity Formula: `15 + (10-Rank) + Prudence*2`

- **Justice**
    > A character's **Speed** Roll and **Movement Points** are increased by their **Justice**.

    Speed Formula: `1d6 + Justice`
    
    Movement Points Formula: `3 + (Justice/2 Rounded Down)`

- **Temperance**
    > A character's max Stagger Resist is increased by their **Temperance**.

    Stagger Resist Formula: `20 + (10-Rank)*2 + Temperance*4`

#### Secondary Stats
> A character's **Secondary Stats** affect their interactions with the environment. This includes **Story Rolls**, interactions with other characters, and capabilities. 

- **Insight**
    > Perception **Story Rolls** are increased by a character's Insight.

- **Other**
    > Other

- **Placeholder**
    > Placeholder

### Proficiencies
> **Proficiencies** define unique abilities that are obtainable every time the character Ranks Up. When a character Ranks Up, they choose 2 Proficiencies to permanently gain. To choose a Proficiency, the character must meet the minimum Stat requirements.

### Augments
> **Augments** allow you to slot **Passives** that affect both combat and exploration. These are unique modifications or additions to a character. Augments allow you to customize your character, and you are encouraged to work with your Game Master to create a unique Augment for your gameplay, appearance, and story. 

### Speed Dice
> **Speed Dice** allow characters to participate in Combat. Having more than one Speed Dice allows a player to slot more Pages in one turn, one per Speed Dice. All characters start with one Speed Dice, and can obtain more through powerful upgrades, milestones, or abilities. Powerful foes may have up to even 4 or more Speed Dice. However, it is highly recommended that the GM control the players' ability to gain Speed Dice, as this is a large power spike for characters. 

## Act 3: Pages
> **Pages** defines the skills, actions, and tools available to a character throughout gameplay. A Page falls into one of either four categories: **Combat Pages**, **Tools**, **Abilities**, and **E.G.O. Pages**.

### Cost
> The **Cost** of a page is displayed on the top left of a Page. To use a Page, a character must pay Light equal to the Cost of the page.

### Page Type
> The **Page Type** is displayed on the top right of a Page. The Page Type affects how and when the Page is used.

#### Melee Pages
> **Melee Pages** can be used against a target who is within the **Weapon Range**. When clashing against a **Ranged Page**, on **Offensive Dice** **Clash Win**, the Dice is not resolved and does not deal damage, instead it is moved to the bottom of the Page.

#### Ranged Pages
> **Ranged Pages** can be used against a target within the **Weapon Range**. When clashing against a Melee Page outside of the target's Weapon Range on **Clash Lose** against a **Defensive Dice** the character takes no Stagger Damage. If no **Offensive Dice** remain on the character's Ranged Page and the character is outside the target's Weapon Range, all Offensive Dice on the target's page converted to **Counter Dice**.

#### Mass Attack Pages
> **Mass Attack Pages** can be used against a number of targets within the **Weapon Range**. The character may choose which Speed Dice of the targets are selected for targetting. When Clashing against a Mass Attack Page, Counter Dice are kept, but not rolled against Mass Attacks. 

- **Summation**
    > To resolve a **Summation** Clash, the sum of all non-**Counter Dice**'s Final Powers on the character's Page is compared to the sum of all non-Counter dice's Final Powers on the target's Page, regardless of whether they were clashing with the Mass Attack or not. If the sum of the target's Dice is lower, all Dice on the target's page excluding Counter Dice are **Negated**. If the sum of the target's dice is equal to or higher, the target is not affected by the Mass Attack. Then, the Mass Attack Page is resolved as One Sided Attack against all remaining targets.

- **Individual**
    > To resolve an **Individual** Clash, resolve each Dice on the Mass Attack Page top to bottom. Each target also resolves their Dice, excluding **Counter Dice** top to bottom. Each target compares their Dice's Final power against the character's Mass Attack Dice's Final Power. If the target's Final Power is lower, the target's Dice is **Negated** and the character's Mass Attack Page's Dice is applied against the target. Repeat for all targets.

#### Instant Pages
> When using an **Instant Page**, the Page is instantly resolved. Instant Pages cannot engage in Clashes. Instant Pages can be used on the character who uses it. Instant Pages can be Items, Proficiencies, or Passive Abilities. 

### Page Clashing
> When a character slots a Page against a Speed Dice that has a Page Slotted, these two pages engage in a **Clash**. When two Pages Clash, resolve each Page from top to bottom. The **Dice** on each Page engage in **Dice Clashes** until the Page is resolved. When clashing against a Mass Attack Page with more than 1 target, the Clash is not resolved until the start of the Mass Attack Page's Owner's turn.

### Page Negating
> When a Page is **Negated**, it is removed from the current clash and immedietly sent to the character's **Discard** without resolving any of the remaining Dice.

### Dice
> **Dice** allow characters to deal damage and defend themselves. Every Dice is either an **Offensive**, **Defensive**, or **Counter** Dice. Every Dice has a assigned **Roll** and **Base Power**. When resolving a Dice, add the result of the Roll to the Base Power to find it's **Final Power**.

#### Recycling
> When a Dice is **Recycled**, it is reused. All **Effects** and **Passives** that affect the Dice persist. It is treated as the same current Dice; Effects and Passives that affect the *next Dice*, do not influence this Recycled Dice.

#### Dice Negating
> When a Dice is **Negated**, it is removed from the current Clash or One Sided Attack. It applies no damage or effects. 

#### Dice Clashing
> When two Dice **Clash**, their Final Powers are compared against each other. The higher Dice is counted as a **Clash Win**, and the lower Dice is counted as a **Clash Lose**. When the Final Powers are equal, it is counted as a **Draw** for both Dice. In the event of a Draw, both Dice are **Negated** and no Sanity is lost or gained. On a Dice's Clash Lose, a character loses 1 Sanity. On a Dice's Clash Win, a character heals 1 Sanity.

#### Offensive Dice
> **Offensive Dice** have an assigned **Damage Type** that characters can have weaknesses or resistances to. Offensive Dice allow the character to damage their target by: `(Final Power)*(Target Resistance)` Rounded Up, where Target Resistance is the target's **Type Resistance** to the specified Damage Type. They also deal Stagger damage equal to `(Final Power)*(Target Stagger Resistance)` Rounded Up, where Target Stagger Resistance is the target's **Type Stagger Resistance** to the specified Damage Type

- **Slash Dice**
    > **Slash Dice** deal and interact with **Effects** and **Passives** that influence **Slash Damage**.

- **Pierce Dice**
    > **Pierce Dice** deal and interact with **Effects** and **Passives** that influence **Pierce Damage**.

- **Blunt Dice**
    > **Blunt Dice** deal and interact with **Effects** and **Passives** that influence **Blunt Damage**.

#### Defensive Dice
> **Defensive Dice** allow characters to reduce or evade damage. Unused Defensive Dice are converted into **Counter Dice**.

- **Block Dice**
    > **Block Dice** allow a character to reduce incoming damage, negate it entirely, and deal Stagger Damage to the attacker. On **Clash Lose**, Incoming damage, before **Type Resistance** is reduced by the Block Dice's Final Power. On **Clash Win**, the attacker takes Stagger Damage equal to the difference in the Block Dice's and the opposing Dice's Final Powers, unless otherwise stated. On Clash Win against Defensive Dice, deal Stagger Damage equal to the Block Dice's Final Power instead.

- **Evade Dice**
    > **Evade Dice** allow a character to avoid incoming damage and recover Stagger Resist. Clashes between two Evade Dice are treated as a **Draw**, regardless of the results. On **Clash Win**, recover Stagger Resist equal to the Evade Dice's Final Power. On Clash Win against an Offensive Dice, Recycle the Evade Dice.

#### Counter Dice
> **Counter Dice** can be Offensive or Defensive. Counter Dice do not prompt any action, and are instead stored on the character until the end of their next **Upkeep**. These Counter Dice are automatically used to respond to any One-sided attack they would receive, used in the order they were generated. They are not used when the character and attacker both slotted a Page in a Clash. On **Clash Win**, Counter Dice are Recycled. Then, at the end of the attacker's Combat Page Resolution, they are lost.

### Combat Pages
> **Combat Pages** are pages derived from your current **Weapons**. Equipment bring at least one **Basic Page**, and can include more **Special Pages**.

### Tools
> **Tools** are pages derived from items in your **Inventory**. Some tools are reusable, while others' pages are consumed upon use.

### Abilities
> **Abilities** are pages derived from **Augments** or your currently equipped **Trinket**.

### E.G.O. Pages
> **E.G.O. Pages** act as combat pages, accessible through character progression. These are unique pages to the character.

## Act 4: Equipment
> **Equipment** grants the Pages that constitute a character's Deck. A piece of equipment falls into one of either two categories: **Weapons** or **Armors**. Each piece of equipment comes with at least one **Page** to use when in a character's **Deck** when equipped.

### Weapons
> **Weapons** provide Combat Pages for the character to use throughout their journey. By default, characters have two hands and can equip up to two hands worth of weapons at a time. This can be increased through **Passives**. Weapons, too, can be modified with Passives.

#### Creating a Weapon
> When creating a Weapon, choose the **Weapon Range** (Melee or Ranged), **Weapon Property** and **Weapon Type**. These affect how the weapon can be used and give benefits. Melee Weapons cannot run Ranged Pages.

**Melee Weapon Properties**

> Melee Weapons, by default have 1 Range.

- **Small**
    - One Handed
    - Adding a new Dice to a Page costs `2` **Page Points** instead of `3`

- **Medium**
    - Two Handed
    - Gain `1` extra **Weapon Point** per Weapon Rank from 9, plus one. For example, a Rank 9 Weapon gets 1 extra Weapon Point, and a Rank 8 Weapon gets 2.                                     

- **Heavy**
    - Two Handed
    - Gain `(10 - Weapon Rank) * (Light-1)/2 Rounded Up` extra **Page Point** per Light Cost 

**Ranged Weapon Properties**

> Ranged Weapons allow the character to build Ranged pages. 

- **Low Caliber**
    - 6 Range
    - One Handed
    - Adding a new Dice to a Page costs `2` **Page Points** Instead of `3`

- **High Caliber**
    - 10 Range
    - Two Handed
    - Gain `(10 - Weapon Rank) * (Light-1)/2 Rounded Up` extra **Page Point** per Light Cost 

**Weapon Type**

> A Weapon's Weapon Type affects how the character can Clash with enemies

- **Offensive**
  - When initiating a Clash, the character can choose to instantly resolve it

- **Defensive**
  - Can Clash with any Attack that is targetting an allied character within your Weapon Range

### Armor
> **Armors** can be modified with **Passives** and set the base **Resistances** for a character. These determine how much damage a character takes to each of the three Damage Types.

#### Resistances
> An Armor has 3 **Resistance** values that affect the Final Damage a character would take when hit by an attack of a specified Damage Type. Higher tier armors have lower Resistances, meaning the character takes less damage. Resistances determine how much Health and Stagger Resist Damage the character receives once they are hit. Resistances multiply the damage received depending on their level.

Resistance Levels

| Resistance Level | DMG Multiplier |
| ----------- | ----------- |
| Fatal | `x2` |
| Weak | `x1.5` |
| Normal | `x1` |
| Endured | `x0.5` |
| Ineffective | `x0.25` |
| Immune | `x0` |

All Outfits start with *Normal* Resistances, and then modify Resistances to fit the Resistance Levels of the Outfit’s Rank using the following table:

| Outfit Rank | Health Resistance | Stagger Resistance |
| ----------- | ----------- | ----------- |
| 9 | `1` Fatal, `1` Weak | `2` Fatal |
| 8 | `1` Weak | `1` Fatal, `1` Weak |
| 7 | `1` Weak | `2` Weak |
| 6 | `1` Weak | `1` Weak |
| 5 | All Normal | All Normal |
| 4 | `1` Endured | All Normal |
| 3 | `1` Endured | `1` Endured |
| 2 | `2` Endured | `2` Endured |
| 1 | `2` Endured, `1` Ineffective | `2` Endured, `1` Ineffective |

### Creating Pages

## Act 5: Creating a Character
> When creating a character, a player must consider the build, design, and story of their character. The customization may be limited or expanded by the Game Master, but in general new characters are composed of these pieces: Starting Rank, Primary Stats, Secondary Stats, Proficiencies, Augments, and Equipment.

### Step 1: Determine Starting Rank
> The Rank a character is determines everything that is available for customization, from Stats, Passives, Equipment and more. So, it is critical to ensure that you and your Game Master have agreed upon a starting Rank for each character. For most campaigns, it is encouraged to start at Rank 9. 

#### Character Stats by Rank
| Rank | Primary Stats | Secondary Stats |
| ----------- | ----------- | ----------- |
| **9** | 4 | 6 |
| **8** | 6 | 9 |
| **7** | 8 | 12|
| **6** | 10 | 15 |
| **5** | 12 | 18 |
| **4** | 14 | 21 |
| **3** | 16 | 24 |
| **2** | 18 | 27 |
| **1** | 20 | 30 |


### Step 2: Assigning Stats
> When you have decided on a starting Rank, you now have a set amount of Primary and Secondary Stats to allocate. These also change what Proficiencies are available to you, so work towards creating a "build" from these Stat assignments. 

### Step 3: Choosing Proficiencies
> After assigning Stats, you can choose 2 Proficiencies every rank up, starting with 4. These Proficiencies allow you to fit the history and background of your character. For example, a character who had a background as a workshop fixer might choose Proficiencies in modifiying or creating Weapons.

#### Proficiency Counts by Rank
| Rank | Proficiency Count |
| ----------- | ----------- |
| **9** | 4 |
| **8** | 6 |
| **7** | 8 
| **6** | 10 |
| **5** | 12 |
| **4** | 14 |
| **3** | 16 |
| **2** | 18 |
| **1** | 20 |

### Step 4: Creating an Augment
> Your Augment allows you to create a unique style of gameplay for your character. You can assign Passives based on the character's starting Rank up to the maximum Passive Costs defined in the table below. There are examples available, but you are encouraged to work with your Game Master to create unique Augment Passives for your build.

#### Max Costs Table
| Rank | Max Cost |
| ----------- | ----------- |
| **9** | 4 |
| **8** | 6 |
| **7** | 8 
| **6** | 10 |
| **5** | 12 |
| **4** | 14 |
| **3** | 16 |
| **2** | 18 |
| **1** | 20 |

### Step 5: Crafting Weapons and Armor 
> When creating Weapons or Armor, you are encouraged to work with your Game Master to ensure that it is balanced for the expectations of the campaign. You are encouraged to start with weaker versions of your ideal starting Equipment to leave room for upgrades and customization in the future. First, assign Passives to the maximum Passive Costs defined in the table below. Then, you will work with your Game Master to create Basic Pages and Special Pages for each Weapon. 

#### Max Costs Table
| Rank | Max Cost |
| ----------- | ----------- |
| **9** | 2 |
| **8** | 3 |
| **7** | 4 |
| **6** | 5 |
| **5** | 6 |
| **4** | 7 |
| **3** | 8 |
| **2** | 9 |  
| **1** | 10 |

### Step 6: Finishing Touches
> After creating the backbone of your character, it is time to build its identity. This includes their history, appearance, goals, and personality. 

- **Name, Age, and Height**
> Although these might have limited impact on the mechanics of your gameplay, they have a large role in how your character interacts with the world. Be creative, but realistic to the setting envisioned by the Game Master.

- **Occupation**
> a character's previous or current occupation could have a large impact on what has shaped the decisions of Passives, Proficiencies and Augment. Consider a former Stigma Workshop fixer who has Burn Resistance. This also helps form the start of the party, for example: is your party working for the same office, syndicate, or even wing?

- **Birthplace and Residence**
> In most cases of the City, a character's birthplace and residence are the same. But, this should not limit your character design! Maybe they were born in I-Corp, but evacuated after the surviving the Pianist incident.

- **Appearance**
> A visual description of your character is a great way to introduce your character to the rest of your party and Game Master. This will also impact how other citizens of the City see and interact with them. Maybe they have scars from their past, be creative! Picrew is a great resource to use for creating a design. 

- **Personality**
> Having a defined personality that is available for your Game Master is very helpful for them to plan ahead, and your party for interactions with your character. How does your character respond to stress, to excitement, or fear?

- **Relationships**
> Does your character have a notable history with other characters that your Game Master could use to draw in your character? The more you give, the more the Game Master can use your character, but make sure to leave it open. If you are too restrictive with the history of other characters, the Game Master might find it difficult to weave into the existing setting. When in doubt, work with them to ensure a smooth gameplay experience for everyone.

- **Starting Ahn**
> Given the background and history of your character, this amount may change from what your Game Master has originally set. Make sure to work with them to decide this as well. 

## Act 6: Deckbuilding
> **Decks** provide the method by which characters engage in combat and provide unique ways to interact with their environment. Characters have two decks available to them: **Combat Decks** and **Auxillary Decks**. The Combat Deck is only available during combat. Auxillary Decks are available at all times. 

### Combat Decks
> **Combat Decks**, by default, consist of 12 pages from a character's Weapons. Characters can create this deck from any number of copies of their **Basic Pages** from currently equipped Weapons.Characters can also run unique, **Special Pages**, obtained from their equipment or modifying a Basic Page. While in **Combat**, the character's Combat Deck is shuffled, face down.

#### Basic Pages
> Characters can copy and equip any number of a **Basic Page** into their Combat Deck. 

#### Special Pages
> Some Equipment may come with **Special Pages** by default. They can also be obtained by modifying a Basic Page, where a copy of the modification is added to the Equipment as a Special Page. 

### Modifying Pages
> To modify a page, characters must meet conditions defined by the Game Master. Characters may choose to modify an existing Basic Page or Special Page. When modifying a Basic Page, modifications are made to a copy of the original Basic Page. This modified copy is then added as a Special Page to the equipment.

### Auxillary Deck
> Each character's **Auxillary Deck** is made up of **Tools**, **Abilities**, and **E.G.O. Pages**. Pages from the Auxillary Deck can be used at any time, unless stated otherwise on the Page or by the Game Master.

## Act 7: Core Systems

### Inventory
> A character's **Inventory** consists of a starting maximum of 9 **Slots**. Each Slot can hold up to one Tool or Item. Tools and Items in your inventory are part of your Auxillary Deck. Every character also has, by default, one **Trinket Slot**.

#### Item
> An **Item** is a Material, Ammo, or story piece created by the Game Master. These, by default, take up one Slot can be **Stacking** or **Non-stacking** Items. Stacking Items can hold multiple of the same Item in the same Slot, up to a specified maximum count. Non-stacking Items, on the otherhand must each have their own unique Slot to hold multiple in your Inventory.

#### Trinket
> A **Trinket** is a unique type of Item, these are only active when equipped into the character's **Trinket Slot**. Trinkets provide special benefits when active. 

#### Trinket Slot
> By default, characters have one **Trinket Slot**, which can hold and activate one Trinket. 

### Passives
> **Passives** are modular, always active, effects that can be applied to Weapons, Armors, and Augments. Every Passive has a predetermined **Passive Cost**. The Rank of an Equipment or Augment determines the Maximum Passive Cost that can be applied. Some Passives have a **Negative Passive** variant, which have negative effects to the character. These allow a character to slot more of other Passives to stay below the Maximum Passive Cost. Characters can only slot Negative Passive Cost equal to the Maximum Passive Cost of the Equipment of Augment.   

### Effects
> **Effects** are temporary ailments, buffs, or environmental effects that apply to a character.

### Story Rolls
> **Story Rolls** occur whenever a character faces a mental or physical obstacle, done at the Game Master's discretion. By default, a Story Roll is `1d20 + Appropriate Stat`. By default a failure is defined as rolling **9** or below and a success is **12** or higher. GMs are encouraged to have other outcomes prepared for exceptionally high or low rolls. 

#### Advantage & Disadvantage
> When a character has **Advantage** they replace their next dice roll with dice rolls equal to their count of Advantage plus 1 and choose the highest of the rolls to keep. When a character has **Disadvantage** they replace their next dice roll with dice rolls equal to their count of Disadvantage plus 1 and choose the lowest of the rolls to keep. Lose all Advantage and Disadvantage after resolving the Dice. If a character would gain Advantage while having Disadvantage, the character loses count of Disadvantage equal to the Advantage they would gain.If a character would gain Disadvantage while having Advantage, the character loses count of Advantage equal to the Disadvantage they would gain 

#### Contested Rolls
> **Contested Rolls** require a character to roll a specific stat, or choice of stat, against another target who does the same. In a **Contest** against a target of a stronger Rank, the character suffers a flat penalty to their Roll equal to the difference in Rank. These follow the same rules as Story Rolls, with a default 1d20 roll. In a Contest against a target with a weaker Rank, the character gains a flat bonus to their Roll equal to the difference in Rank. For example, a character with Rank 9 suffers a penalty to their roll of -2 against a target with rank 7. The higher roll wins the Contest. Handling of ties, and exceptionally high or low rolls, are done at the Game Master's discretion.

#### Assist
> A character can **Assist** another character with an action requiring a Story Roll when they are within range of the same action, determined by the Game Master. GMs can require whatever cost they see as appropriate and give whatever benefit they see appropriate. 

### Resting
> **Resting** occurs when a character is able to meet the following conditions for a period of time: out of combat and in shelter. While Resting, characters restore Health and Sanity. Additionally, characters can freely edit their deck, change weapons, and switch armors while resting. For every hour of rest characters recover `6 + (10-Rank)*2 + Fortitude*2` Health and `(10-Rank)*2 + Prudence` Sanity.

### Deck Interactions

#### Hand
> Current Combat Pages available to the character are defined as being in the character's **Hand**. Characters can only slot Pages from their Hand. When a character draws a Page, it is added to their Hand.

#### Drawing
> When a character **Draws** a Page, take one Page from the top of the character's Combat Deck and add it to the character's Hand. If a character's Combat Deck is empty, shuffle their **Discard Pile** face down to replenish their Combat Deck. If the Discard Pile is also empty, the chracter instead does not draw a Page.

#### Discarding
> When a character **Discards** a Page, move the page to the top of their **Discard Pile**, face up. 

## Act 8: Combat

### Combat Start
> On **Combat Start**, all characters roll a `d6 + Justice` to determine **Speed**. Turn order then goes from highest to lowest Speed rolls. Ties go to the players first, then ties between players are decided between the players. Other ties are determined by the Game Master. Each character fully recovers their Light and draws `3` Pages.

### On Your Turn
> Turns, in general, follow this order: **Resolve Slotted Pages**, then **Upkeep**, then **Combat Actions**, and finally **Endstep**. 

#### Resolve Slotted Pages
> To Resolve a Slotted Page that is not **Clashing**, resolve each Dice on the Page from top to bottom. Apply Damage and Effects to the chosen target as specified on the Page. To Resolve a Slotted Page that is Clashing, each dice Clashes against the opposing Page's Dice. After all Dice have been resolved on a Page, the Page is moved to the Discard.

#### Upkeep
> After resolving all Slotted Pages, the character's turn phase moves to **Upkeep**. During this phase, characters first draw a Page from their Combat Deck. Then, characters restore, by default, 1 Light. Then, resolve all Effects and Passives that activate at this time, in the order chosen by the character.

#### Combat Actions
> After resolving all Effects and Passives in the Upkeep phase, the character's turn phase moves to the **Combat Action** phase. Here, characters can choose any number of available **Combat Actions** to perform a turn.

- **Movement:**
    > Every turn a character gets a number of **Movement Points** (`3 + (Justice/2 Rounded Down)`), increased by their Justice and Passives. Characters cannot spend any Movement Points while they are the target of an enemy attack, unless the attack is a Mass Attack. Characters can move tiles in any direction equal to the number of Movement Points expended for this Action. 

- **Use a Combat Page**
    > To use a **Combat Page**, a character must pay Light equal to the Cost of the page. After a character pays the Cost of the Page, the Page is **Slotted** into the chosen Dice Slot against a chosen target until it is resolved.

- **Use an Auxillary Page**
    > Unlike Combat Pages, characters have full access to the Auxillary Deck from the start of combat, unless stated otherwise by the Game Master. After using an **Auxillary Page**, the page is removed from the Auxillary Deck until the end of combat, unless stated otherwise on the Page.

#### Endstep
> When a character is ready to pass their turn, their turn phase moves into the **Endstep**. During the Endstep, all Effects and Passives that activate at this time are resolved in the order chosen by the character.

### Cover
> When a character is in **Cover**, the strength of ranged pages are reduced depending on the amount of Cover, determined by the Game Master. When a character attempts to move into Cover, while a Ranged Page is slotted against the character, the character who has slotted the Page has the choice to instantly resolve the Page. 

#### Partial Cover
> For a character to be in **Partial Cover**, they must have at least 50% of their body covered by an appropriate external source, such as a residential wall or pillar. While a character is in the effects of Partial Cover, Ranged Pages get `Final Power - 2` against the character. Final Power cannot drop below 1 by the effects of Partial Cover.

#### Full Cover
> For a character to be in **Full Cover**, they must be completely covered by an appropriate external source. While a character is in the effects of Full Cover, Ranged Pages cannot be targetted against the character.

### Panic
> When a character reaches their minimum Sanity value, they enter **Panic** until 3 upkeeps have passed. When entering Panic, a character rolls a `d4` to determine their Panic Type. A character can be forcefully recovered from Panic when another character succeeds on a Prudence Story Roll. The result must be **12** or greater to succeed. On failure, subsequent attempts to recover the same character get `+X` to their roll, where `X` is the number of failed attempts. The character is then under the effects of the rolled Panic Type until they naturally recover after 3 upkeeps or are recovered by another character. When a character recovers from Panic, their Sanity is set to 0.

#### Panic Types
- **1: Despair**
    > Every die, including Story Rolls always rolls its minimum. 

- **2: Paralysis**
    > The Character cannot draw Pages by any means. 

- **3: Darkness**
    > The Character cannot gain Light by any means.

- **4: Confusion**
    > The Character cannot use Auxillary Pages.

### Staggered
> When a character's Stagger Resist hits 0, they become **Staggered**. While Staggered, all of their resistances are temporarily set to 2x, Fatal, until they recover from Stagger. Characters also cannot act in any way while Staggered: they cannot use Pages, move or perform any actions. Characters recover from Stagger after 2 upkeeps have passed. So, if a character is staggered, they will pass through their next turn, and then recover on the upkeep of the 2nd turn after.

### Knocked Out
> When a player's character's health reaches 0, they are **Knocked Out**. Another character can make a **Temperance** Story Roll to recover a character. This requires a result of **12** or more to succeed. Subsequent rolls get `+X`, where `X` is the number of failed attempts. When a character is recovered from a Knock Out state, they recover 25% Health or `(Max Health/4) Rounded Down`, `3 + Prudence` Sanity and fully recover their Stagger Resist. The character who recovered the Knocked Out character also recovers `3 + Prudence` Sanity. After three upkeeps have passed without being recovered, the character is considered Dead. Characters can still slot Combat Pages against the Knocked Out character. When the Page resolves, it does not deal any damage or apply any affects to the Knocked Out character. However, all dice are still resolved top to bottom as normal (Defensive Dice become Counter Dice as normal). If the page contained at least 1 Offensive Dice, the Knock Out upkeep counter is reduced by 1 turn. 

### End of Combat
> When combat has ended, fully recover all Light and Stagger Resist to every character. Characters then recover `3 + Prudence` Sanity. Any Panicked characters recover from Panic and any Staggered characters recover from Stagger. Any characters in a Knocked Out state are recovered.

## Act 9: Economy

## Credits
- **altidiya**: Member of the CR 2.0 Dev Team.
- **arbitrary_crow_execution**: Member of the CR 2.0/3.0 Dev Team.
- **beautifuldemise**: Member of the CR 3.0 Dev Team and Roll20 Sheet Dev.
- **blossomingcrow**: Member of the CR 3.0 Dev Team.
- **chromaticmuse**: Member of the CR 1.0 Dev Team.
- **cowts**: Member of the CR 1.0/2.0 Dev Team, creator of the Google Sheet Version English to 1.3.
- **derpete**: Member of the CR 1.0 Dev Team.
- **enzo1770**: Member CR 1.0/2.0 Dev Team.
- **fetlach**: Designer of the Community Rulebook logo.
- **helloing0119**: Original creator of the Korean Rulebook [X link]
- **kreif**: Member of the CR 2.0/3.0 Dev Team.
- **liltdog9510**: Member of the LoR PMTTRPG and SoLP Dev Team
- **mori____**: Member of the CR 2.0/3.0 Dev Team.
- **nonamerce**: Member of the CR 3.0 Dev Team.
- **punibird**: Translator from Korean to English of the Rulebook [X link] and Roll20 Sheet Dev
- **saviorgaming**: Member of the CR 2.0/3.0 Dev Team.
- **soetri**: Member of the LoR PMTTRPG and SoLP Dev Team.
- **suleiman02**: Member of the CR 3.0 Dev Team.
- **sky______**: Member of the CR 3.0 Dev Team.
- **snarkmcclark**: Member of the CR 2.0/3.0 Dev Team.
- **xiaqia**: Member of the CR 2.0/3.0 Dev Team.
- **zetsubots**: Member of the CR 3.0 Dev Team.
- **.kiibo**: Member of the CR 3.0 Dev Team.