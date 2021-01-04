# CHARACTER CRAFT :: TO BE 1/3/2021
## Background / Problem Statement
In Dungeons and Dragons, the character sheet is used to record information about the player character's statistics, equipment, and progress towards improvement. 
Traditionally, this is done with pencil on a printed template, which brings about problems associated with single-source physical documents. For example, as the character improves, the player will have to erase and re-write numbers frequently. 

## MVP Scope
To solve the above problems with a physical character sheet, we want a digital character sheet that will empower the user to:
- Set
- Store
- Update

all relevant character attributes and retrieve them at a later date. 
In future iterations, we can add logic to automate calculations for derived fields.
The current sheet looks like this:  

![image](https://user-images.githubusercontent.com/59585235/103493306-88f93f00-4dfe-11eb-8f08-ba54210a3434.png)

We will create a webapp that will act as a persistent, digital character sheet.

## Assumptions
Maintaining fifth edition character sheet (not other versions, or other games) will support most players for the foreseeable future. 
Lists of existing character data will meet reasonable data size expectations.
Will only support material from base D&D lists (Player Handbook and Dungeon Master's Guide).
Will not support multiclassing features. 

## High Level Requirements
Supported fields:
Datatype to be decided by technical team. 
Titles are for guidance  only- for example, Abilities is not a field, but the title of the character sheet section. 

Abilities 
- Strength 
- Dexterity
- Constitution
- Intelligence
- Wisdom
- Charisma

Character Description 
- Character Name 
- Class 
- Level 
- Background 
- Race 
- Alignment
- Experience Points 
- Age 
- Height 
- Weight 
- Eyes 
- Skin
- Hair 

Skills 
- Acrobatics
- Animal Handling 
- Arcana
- Athletics
- Deception
- History
- Insight
- Intimidation
- Investigation
- Medicine
- Nature
- Perception
- Performance
- Persuasion
- Religion
- Sleight of Hand
- Stealth
- Survival

Saving Throws 
- Strength 
- Dexterity
- Constitution
- Intelligence
- Wisdom
- Charisma

Health 
- Armor Class 
- Initiative
- Speed
- Current Hit Points
- Temporary Hit Points
- Hit Dice
- Total Hit Dice
- Death Saves (3 success radios, 3 failure radios)

Unaffiliated Skills 
- Inspiration
- Proficiency Bonus
- Passive Wisdom (Perception)
- Other proficiences and languages
- Features & Traits 

Attacks and Spellcasting 
- Weapon Name
- Atk Bonus
- Damage/Type 

Equipment
- PP
- GP
- EP
- CP
- GP
- Blank Field for additional equipment

Personality 
- Personality Traits
- Ideals
- Bonds
- Flaws

Second Page
- Character Appearance
- Character Backstory
- Allies & Organizations
- Additional Features & Traits
- Treasure
- Symbol and Symbol Name 

## Open Questions
Support spellcasting? 
Support math for future iteration? (re:datatypes)  
Support Runequest? (closed, off-topic)  
How does technical want to present possible extra fields to user (see Attacks and Spellcasting, Equipment)? 
How does technical want to handle symbol and symbol name





