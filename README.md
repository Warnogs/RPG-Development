# RPG-Development
> I will make this a real .html page and not eye bleeding eventually...

> For now, you can use an extention like https://darkreader.org/

# Dialogue Folder Structure:
**Each Character should have their own Dialogue Category**

**QUEST DIALOGUE SHOULD BE KEPT SEPERATE**

**Example Structure:**

![Dialogue Organization](./Example%20Images/DialogueOrganization.png)

# Dialogue Options Formatting:
## For Actions
### *There should be () encapsulating the action in **LOWER-CASE***
**Example:**
> (say hello)

## For Actual Speech
### *There should be ellipses ... before any message intended for the character to be said*
**Example:**
> ...hello..!?

## CLOSE Options at the Bottom! 
> *Use the Last Slot (6) for Leave in case we need to add more options later*

## Option Colours for Quests:
### Speaking Dialogue Options for the Main Quest must be gold 
> #FFAA00

### Speaking Dialogue Options for **Side Quests** should be aqua
> #00AAAA

### Other Options should be white
> #E0E0E0

> **Note**: *To have the first digit in place you have to click on a similar colour with the same first hex digit!*
> *For example if you want to do 00AAAA it will have an E at the front like E00aaaa and will not work*

# Dialogue Start:
## Recursive Characters:
> *Some characters will be reused*

> They will need a Main Menu Dialogue

## Non-Recursive Characters:
> *These characters are single-purpose*

> It is acceptable to not have a main menu dialogue for these characters, but it is best practice to make one, in case we want to make them recursive

**Recursive Character Main Menu Example:**

![Dialogue Menu](./Example%20Images/DialogueMenu.png)

# Quest Naming:
Please Name your quests like
> **[Quest Segment #] [Quest Name]**

**Example:**

![Quest Names](./Example%20Images/QuestNames.png)

# Quest Dialogue Naming:
> **[Quest Segment #]-[Dialogue Segment #] [Description]**

> ***Note:** this name **can be seen in the quest log** if you set a dialogue as an **end goal of a quest***

## When making Quest Dialogue Category:
> Make sure you add the word "Quest" in the category name
> Also make sure you put ! before the quest category (not shown in image)

**Quest Dialogue Naming Example:**

![Quest Dialogue Names](./Example%20Images/QuestDialogueNames.png)
> in this example, **"SlumWeaponQuest"** category should be named **"! Slum Weapon Quest"**

# Regular Dialogue Naming
> **[Layer #]-[Option #] [Description]**

**Dialogue Naming Example:**

![Dialogue Names](./Example%20Images/DialogueNames.png)

> ***Note:** these dialogue names will never be visible, so this naming scheme is to help developers differentiate dialogues*

**Intended Naming Result:**

![Dialogue Names Tree](./Example%20Images/DialogueNamesTree.png)
