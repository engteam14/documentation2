   2. Requirements


# Elicitation of requirements



1. The provided product brief indicated the overall goals and intentions of the finished product and contained general descriptions of its desired functionality
2. Group brainstorming session was held to compare our interpretations of the brief and to raise a list of questions to address to the customer
3. In a group meeting with the customer, answers to the questions and any other customer comments were detailed in informal meeting notes.
4. Recorded info was formalised as a set of user requirements.
5. User requirements were distilled down into more specific functional and non-functional requirements.
    1. Functional requirements detailed concrete, specific functionality and capabilities of the product as related to its software implementation.
    2. Non-functional requirements captured the performative characteristics of the completed product as a whole which could be perceived by the user or tester.
6. Resulting functional and non-functional requirements were closely evaluated for possible risks to their implementation; these were detailed within the risk register.


# Research into requirement specification and presentation



* IEEE requirements engineering document<sup>1</sup>:
    * Provided comprehensive information on all aspects of requirement elicitation and presentation, although sections 5.1-5.2.8 and 6.1-6.6.3 were most helpful
    * Contained robust justification for the need for requirements and their role in the overall software lifecycle process
    * Informed our choice of specific language, standardised subjects and verbs (user, shall, etc.), the choice of imperative tone, and justifications for these
    * Ultimately, aimed at larger, more critical projects than ours
* ENG1 lecture on requirements engineering:
    * Provided an excellent overview of the motivations for requirements engineering and a lucid overview of this process
    * Introduced the user/functional/non-functional requirements methodology which proved an excellent fit for our scope of project (versus lifecycle-based requirement methodology in the IEEE document)
    * Demonstrated requirements tables as a tool for writing down and detailing requirements

    Informed by these resources, we chose a tabular format for implementing for the requirements register, allowing us to easily add additional metadata to individual rows as extra columns and permitting a quick, comprehensive overview of the entire register. All rows were labeled with unique identifiers, permitting cross-referencing between user and


    (non-)functional requirements, as well as with other sections of project documentation, such as the risk register and architecture specs.


    <sup>1</sup> _Systems and software engineering -- Life cycle processes -- Requirements engineering_, ISO/IEC/IEEE 29148:2018(E), 2018.


                                **User Requirements**


<table>
  <tr>
   <td>
    <strong>Category</strong>
   </td>
   <td>
    <strong>ID</strong>
   </td>
   <td>
    <strong>Description</strong>
   </td>
   <td>
    <strong>Priority</strong>
   </td>
  </tr>
  <tr>
   <td>
    Game setting
   </td>
   <td>
    UR_PLATFORM
   </td>
   <td>
    The user shall use a standard laptop PC to play the game
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Game setting
   </td>
   <td>
    UR_GAME_INIT
   </td>
   <td>
    The user shall begin a new game from an initial state
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Game setting
   </td>
   <td>
    UR_SHIP_CONTROL
   </td>
   <td>
    The user shall control a ship sailing across the great Lake of York
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Game setting
   </td>
   <td>
    UR_COMPETING_COLLEGES
   </td>
   <td>
    The user shall encounter at least 3 other colleges
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Game setting
   </td>
   <td>
    UR_LEARNING_CURVE
   </td>
   <td>
    The user shall play the game without training
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Game setting
   </td>
   <td>
    UR_GAME_DURATION
   </td>
   <td>
    The user shall be able to complete the game within a ~5 minute timespan
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Game setting
   </td>
   <td>
    UR_GAME_OBSERVABILITY
   </td>
   <td>
    The game shall accomodate onlookers in the PCs surroundings
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_FRIENDLY_SHIP_ENCOUNTER
   </td>
   <td>
    The user shall encounter friendly NPC ships
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_HOSTILE_SHIP_ENCOUNTER
   </td>
   <td>
    The user shall encounter hostile NPC ships
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_FIRE_WEAPONS
   </td>
   <td>
    The user shall be able to fire weapons from the ship
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_BULLET_DODGE
   </td>
   <td>
    The user shall be able to maneuver their ship to dodge fired munitions
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_FRIENDLY_BUILDING_INTERACT
   </td>
   <td>
    The user shall interact with friendly buildings
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_HOSTILE_BUILDING_COMBAT
   </td>
   <td>
    The user shall engage in combat with hostile buildings
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_HOSTILE_COLLEGE_CAPTURE
   </td>
   <td>
    The user shall capture other colleges via combat
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Earnables
   </td>
   <td>
    UR_EARN_MONEY
   </td>
   <td>
    The user shall earn money
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Earnables
   </td>
   <td>
    UR_EARN_POINTS
   </td>
   <td>
    The user shall earn points
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Earnables
   </td>
   <td>
    UR_EARN_XP
   </td>
   <td>
    The user shall earn XP
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    Progress
   </td>
   <td>
    UR_QUEST_PROGRESS
   </td>
   <td>
    The user shall progress through a series of quests
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Progress
   </td>
   <td>
    UR_GAME_WIN
   </td>
   <td>
    The user shall win the game through achieving an ultimate objective unlocked by the fulfillment of preceding requirements/quests
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Progress
   </td>
   <td>
    UR_GAME_LOSE
   </td>
   <td>
    The user shall lose the game through being defeated in combat
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_SHIP_COMBAT
   </td>
   <td>
    The user shall engage in combat with other ships
   </td>
   <td>
    Assessment 2
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_OBSTACLE_ENCOUNTER
   </td>
   <td>
    The user shall encounter obstacles while sailing in game
   </td>
   <td>
    Assessment 2
   </td>
  </tr>
  <tr>
   <td>
    Encounters
   </td>
   <td>
    UR_WEATHER_ENCOUNTER
   </td>
   <td>
    The user shall encounter bad weather while sailing
   </td>
   <td>
    Assessment 2
   </td>
  </tr>
  <tr>
   <td>
    Earnables
   </td>
   <td>
    UR_SPEND_MONEY
   </td>
   <td>
    The user shall spend the money earned
   </td>
   <td>
    Assessment 2
   </td>
  </tr>
</table>



                            **Functional Requirements**


<table>
  <tr>
   <td>
    <strong>ID</strong>
   </td>
   <td>
    <strong>Description</strong>
   </td>
   <td>
    <strong>User requirement</strong>
   </td>
   <td>
    <strong>Risks</strong>
   </td>
   <td>
    <strong>Priority</strong>
   </td>
  </tr>
  <tr>
   <td>
    FR_MENU_KB_INPUT
   </td>
   <td>
    The game shall accept keyboard input for menu navigation
   </td>
   <td>
    UR_PLATFORM
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_VIEWPORT_SCALING
   </td>
   <td>
    The game shall render on a 13"-27" monitor
   </td>
   <td>
    UR_PLATFORM
   </td>
   <td>
    R6
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_MIN_FPS
   </td>
   <td>
    The game shall render at a minimum of 30 FPS
   </td>
   <td>
    UR_PLATFORM
   </td>
   <td>
    R7, R3
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_CROSS_PLATFORM_WIN
   </td>
   <td>
    The game shall be playable on Windows
   </td>
   <td>
    UR_PLATFORM
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_CROSS_PLATFORM_MAC
   </td>
   <td>
    The game shall be playable on Mac OS
   </td>
   <td>
    UR_PLATFORM
   </td>
   <td>
    R9, R10
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_CROSS_PLATFORM_GNU_LINUX
   </td>
   <td>
    The game shall be playable on GNU/Linux
   </td>
   <td>
    UR_PLATFORM
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_GAME_RESET
   </td>
   <td>
    The game shall allow restarting play from an initial configuration
   </td>
   <td>
    UR_GAME_INIT
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_SHIP_KB_INPUT
   </td>
   <td>
    The game shall accept keyboard input for ship control
   </td>
   <td>
    UR_SHIP_CONTROL
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_COLLEGE_ENTITY_TRACKING
   </td>
   <td>
    The game shall keep track of ships and buildings for a minimum of 3 distinct factions
   </td>
   <td>
    UR_COMPETING_COLLEGES
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_FRIENDLY_AI
   </td>
   <td>
    The game shall control the actions of friendly ships
   </td>
   <td>
    UR_FRIENDLY_SHIP_ENCOUNTER
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_FRIENDLY_INTERACT
   </td>
   <td>
    The game shall allow user interaction with friendly ships
   </td>
   <td>
    UR_FRIENDLY_SHIP_ENCOUNTER
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_HOSTILE_AI
   </td>
   <td>
    The game shall control the actions of enemy ships
   </td>
   <td>
    UR_HOSTILE_SHIP_ENCOUNTER
   </td>
   <td>
    R1
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_PLAYER_FIRE
   </td>
   <td>
    The game shall enable the user to fire ship weapons
   </td>
   <td>
    UR_FIRE_WEAPONS
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_PLAYER_AMMO
   </td>
   <td>
    The game shall maintain the state of the user's ship armament and ammunition
   </td>
   <td>
    UR_FIRE_WEAPONS
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_BULLET_TRAVEL
   </td>
   <td>
    The game shall render the travel of a ship's fired munition
   </td>
   <td>
    UR_BULLET_DODGE
   </td>
   <td>
    R2
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_MONEY_TRACKING
   </td>
   <td>
    The game shall keep track of a player's money
   </td>
   <td>
    UR_EARN_MONEY
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_MONEY_UPDATE
   </td>
   <td>
    The game shall give money on success in quests and encounters
   </td>
   <td>
    UR_EARN_MONEY
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_POINTS_TRACKING
   </td>
   <td>
    The game shall keep track of a player's points
   </td>
   <td>
    UR_EARN_POINTS
   </td>
   <td>
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_POINTS_UPDATE
   </td>
   <td>
    The game shall give points with time survived and obstacles navigated
   </td>
   <td>
    UR_EARN_POINTS
   </td>
   <td>
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_XP_TRACKING
   </td>
   <td>
    The game shall keep track of a player's XP
   </td>
   <td>
    UR_EARN_XP
   </td>
   <td>
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_XP_UPDATE
   </td>
   <td>
    The game shall give XP on successful combat encounters completed
   </td>
   <td>
    UR_EARN_XP
   </td>
   <td>
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_QUEST_TRACKING
   </td>
   <td>
    The game shall maintain the state of the user's progress through multiple objectives
   </td>
   <td>
    UR_QUEST_PROGRESS
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_QUEST_RANDOMISE
   </td>
   <td>
    The game shall randomise user's objectives between different playthroughs
   </td>
   <td>
    UR_QUEST_PROGRESS
   </td>
   <td>
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_QUEST_OBJECTIVE
   </td>
   <td>
    The game shall associate quest objectives with game entities
   </td>
   <td>
    UR_QUEST_PROGRESS
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_BOSS_UNLOCK_TRACKING
   </td>
   <td>
    The game shall monitor quest progression status prior to unlocking final objective
   </td>
   <td>
    UR_GAME_WIN
   </td>
   <td>
   </td>
   <td>
    Shall
   </td>
  </tr>
  <tr>
   <td>
    FR_BOSS_SPAWN
   </td>
   <td>
    The game shall spawn boss upon final objective ready status
   </td>
   <td>
    UR_GAME_WIN
   </td>
   <td>
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_GAME_WIN
   </td>
   <td>
    The game shall display game stats upon successful completion of boss encounter
   </td>
   <td>
    UR_GAME_WIN
   </td>
   <td>
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_PLAYER_DEFEAT
   </td>
   <td>
    The game shall display game stats upon player defeat
   </td>
   <td>
    UR_GAME_LOSE
   </td>
   <td>
   </td>
   <td>
    May
   </td>
  </tr>
  <tr>
   <td>
    FR_SCENARIO_FAIL
   </td>
   <td>
    The game shall display game stats upon game over scenario completion
   </td>
   <td>
    UR_GAME_LOSE
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



                                **Non-Functional Requirements**


<table>
  <tr>
   <td>
    <strong>ID</strong>
   </td>
   <td>
    <strong>Description</strong>
   </td>
   <td>
    <strong>User requirement</strong>
   </td>
   <td>
    <strong>Fit criteria</strong>
   </td>
   <td>
    <strong>Risks</strong>
   </td>
  </tr>
  <tr>
   <td>
    NFR_SHIP_COLLISIONS
   </td>
   <td>
    The game shall detect collisions between different ships
   </td>
   <td>
    UR_HOSTILE_SHIP_ENCOUNTER
   </td>
   <td>
    Distance between drawn assets &lt;5px
   </td>
   <td>
    R4
   </td>
  </tr>
  <tr>
   <td>
    NFR_WORLD_COLLISIONS
   </td>
   <td>
    The game shall detect collisions between ships and world objects
   </td>
   <td>
    UR_COMPETING_COLLEGES
   </td>
   <td>
    Distance between drawn assets &lt;5px
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
    NFR_BULLET_COLLISIONS
   </td>
   <td>
    The game shall detect collisions between game entities and fired munitions
   </td>
   <td>
    UR_BULLET_DODGE
   </td>
   <td>
    Distance between drawn assets &lt;5px
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
    NFR_USER_INPUT_LAG
   </td>
   <td>
    The game shall be responsive to user input
   </td>
   <td>
    UR_SHIP_CONTROL
   </td>
   <td>
    Input lag &lt;200ms
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
    NFR_AI_LAG
   </td>
   <td>
    NPC actions' responsiveness shall approximate that of player actions
   </td>
   <td>
    UR_HOSTILE_SHIP_ENCOUNTER
   </td>
   <td>
    AI response time &lt;200ms
   </td>
   <td>
    R3
   </td>
  </tr>
  <tr>
   <td>
    NFR_RENDER_SMOOTHNESS
   </td>
   <td>
    The game world shall render smoothly during player movement
   </td>
   <td>
    UR_SHIP_CONTROL
   </td>
   <td>
    Visual render lag &lt;200ms
   </td>
   <td>
    R8
   </td>
  </tr>
  <tr>
   <td>
    NFR_COLOURBLINDNESS
   </td>
   <td>
    Game map and assets should be distinguishable by a colourblind person
   </td>
   <td>
    UR_PLATFORM
   </td>
   <td>
    Subjective screenshot test via colourblind accessibility evaluation app
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
    NFR_EASE_OF_USE
   </td>
   <td>
    The game shall be self-explainable and feature obvious controls
   </td>
   <td>
    UR_LEARNING_CURVE
   </td>
   <td>
    Tester must be able to pick up and play with no prior instruction
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
    NFR_GAME_DURATION
   </td>
   <td>
    The game shall finish within ~5 mins in a win or loss for the player
   </td>
   <td>
    UR_GAME_DURATION
   </td>
   <td>
    Tester must reach the game stats screen within 4-6 mins
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
    NFR_LARGE_ASSETS
   </td>
   <td>
    The game assets shall be large enough to observe from several metre's distance away on a standard laptop PC screen
   </td>
   <td>
    UR_GAME_OBSERVABILITY
   </td>
   <td>
    Observer standing 2m away should be able to answer questions about gameplay state
   </td>
   <td>
   </td>
  </tr>
</table>

