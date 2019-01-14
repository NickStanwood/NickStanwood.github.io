# Hobby Projects

## Pathfinder World Builder

The Pathfinder World Builder allows a Dungeon Master to create an entire world from start to finish for a pathfinder campaign. The application is designed to be as inclusive in the design process as the user needs. If they want to store everything, right down to the name of the butcher in a town 200 miles away from the main plot of the story, they are more than welcome to. If they prefer to keep only the main plot points stored, that works just as well.

Getting started is easy. The application will walk you through the initial steps of designing a world, and then filling in the rest is up to you (mostly).
![Image of Flow Chart](NickStanwood.github.io/WorldBuilderFlowChart.png)

  - Create the world map
    - Height Map
    - Heat Map
    - Moisture Map
    - Biome Map (relies on height, heat and moisture)
    - Mountains
    - Rivers (relies on moisture and mountains)
  - Create the Pantheon(s) of Gods
    - Type of Magic
    - Alignments
    - Relationships (who likes/hates who)
  - Create Religions
    - Pantheon or fraction thereof
    - Beliefs
  - Create Races
    - Stats
      - Ability Scores
      - Size
      - Type
      - Base Speed
      - Languages
      - Racial Traits
      - Average Height and Age
    - Physical Description
    - Prefered Environment
    - Society Integration Level
    - Beliefs
    - Relationships with other Races  
  - Create Political Map
    - assign territories (based on rivers and mountains)
    - create towns, cities and capitals 
  
  - Start a Campaign
    - Create an Adventure
    - Create Events for that adventure
    - Repeat.
    
After doing these steps, you can begin to fill in as many details as you feel neccesary. This is where the real rabbit hole begins.     
  >Sure, the adventurers may never go to this town, but just in case, I'll make sure every NPC's rich family history is thuroughly thought out. 


### World Wiki
The world history allows you to kep track of all the information you have deisgned for your world. anything in the wiki can be referred to in other parts of the application. 

### World Map
The world map is created at the very beginning. It consits of:
- Geographical Map
  - Height May
  - Heat Map
  - Moisture Map
  - Biome Map
- territory Map
  - Territories
  - Town / Cities
  - Roadways
  - Religions

### Campaign Timeline
Ideally the timeline will allow you, as the DM, to run a railroad-ish campaign that still feels completely open sandbox to the players. If things do get too far off track however, thats what the **Dungeon Creator**, **Town Creator**, and **Character Creator** are for. The timeline is easily modifiable so no parts of your story need to be set in stone. 

### Dungeon Creator
You had a busy week and now you don't have a session prepared? No problem, use the random dungeon creator for your adventurers to go dungeon crawling for the day. Complete with random encounters in *mostly* every room, and lots of loot. Only requires the party level, the number of adventurers, and the estimated time to clear to create the dungeon. A theme can also be chosen for a more immersive experience. Complete with a DM map for you and an adventurers map for them.

### Town Creator
Has the party made some unexpected decisions, and now you find yourself in desperate need of a town of 600 people? No problem, use the random Town Creator to design a town, complete with a map layout and merchants. You can even add random story hooks that can take your adventurers to a dungeon. The only things required from you are the terrain of the town, the size (village, town, city or capital). Districts of the city can be added or excluded as you see fit.  
- Town Map
  - one for Adventurers
  - one for the GM
- Government/Royalty
  - Randomized differently depending on the government/Royalty that is established in the territory
- Merhcants
  - Blacksmiths
  - Magic Items
  - Alchemist
  - Odds and Sods
- Churches 
  - Only available if a pantheon of gods has been set up
- Inns

### Character Creator
Need an NPC on short notice for your adventurers to fight or possibly even team up with? No Problem, input as much information as you'd like into the Character Creator and it will use the optimization level you specify to randomize the rest of the information. the lower the optimization, the more *interesting* the results. Going with max optimization may net you an Orc barbarian that has the potential to break every bone in your adventurers body's. Or going with minimum optimization means you might end up with a goblin wizard that only has one arm, and spells that all require a somatic component. 

## Recaman Sequence

What was this one? I cant freakin remember.

## A258107

Looks to confirm if 2, 3, 4, 82000 are the only terms in the OEIS A258107 Series. So far no catches on a new term

## Pokemon Creator

Ever wanted to create your own pokemon? Ever wondered what a frankenstein like creation would look like from the parts of the original 151 pokemon? look no further. This app lets you do exactly that.

# Academic Projects

## TI MSP-430 Assembly language compiler

Takes in a .txt file filled with an assembly program for the TI MSP-430 microprocessor. Outputs an S-record of the compiled data. 

## MSP-430 Emulator

Takes in an S-record of compiled assembly code and runs it on an emulator for the TI MSP-430. the emulator is debuggable, so each instruction of the program can be stepped through.

## Real-time Operating System for a Model Train Set

Controlled two model trains that zoomed around a model track. Each train had specific locations it needed to stop at, and the controller would ensure no collisions would occur.

# Topco

## Customer Command Center

The Customer Command Center is a web based application that allows clients of the Topco Oil Analyzer to view the output of their frac pumps from anywhere. 

## Oil Analyzer DataWarehouse

Stores all the data acquired by the sensor packages. Runs the ML algortihm on this data and sends out updates to the trucks when there is a new algorithm available.

## Truck Simulator

Allows for testing the UI of the website without needing an actual truck pressent. sends randomized sensor data to the DemonstrationDataWarehouse, so the values do not interfere with the actual truck's data.
