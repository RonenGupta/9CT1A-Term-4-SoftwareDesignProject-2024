# **Cyber Defense - Planning and Overview**

## **Identifying and Defining**

**Need:**

 With the increasing amounts of cyber threats occuring, there is a need for educational tools to inform and teach individuals about cyber security principles and safe online practices. Children in particular, lack this awareness of common threats and how to protect themselves.

**Problem Statement:** 

As cyber attacks become more sophisticated, children alike remain unprepared and unprotected to these threats. By making a gamified version of a cyber defense in real life similar to tower defense games, this can create an interactive platform where they can battle against certain threats, and experiment with different protection systems to practice defensive strategies and be informed about how to counter these threats.

**Skill Development:**

- Unity Skills: To develop the skills needed to create the game, I would complete tutorials on Unity in tower defense game development and any other advanced features such as custom UI creation and possible 3D modelling.

- Cyber security Knowledge: Develop any knowledge to represent real life cyber security threats and defensive systems.

- Game Balancing: Ensuring progressive difficulty, so the user learns and adapts strategies to different types of threats.
***

### **Requirements Outline**

**Inputs:**

- Mouse clicking: (For selecting defensive strategies, placing them, upgrading them, selling them or skipping waves)

- Dragging with mouse: (For moving towers to a certain area where you want.)

- Keyboard shortcuts for quick actions: (Pausing or quick upgrading a tower with a key.)

**Processing:**

- Threat logic: Will spawn certain threats in waves each with different abilities such as speed, resilience, or splitting into multiple more threats at death. If a wave has passed fully, or skipped by the user's input, the system will carry out the threat logic listed.

- Tower logic: Towers will each have different abilities corresponding to each threat, such as being more effective in slowing, damaging, or being faster in responding to such threats. Most towers will possess the ability to damage every threat, however some will be less effective, teaching children to use the correct strategies to combat the threat. The system detects if a threat is in the radius of the tower, and the tower reacts accordingly to the instructions listed above.

- Score and Hearts: Score is deduced through how many threats are eliminated and how strong some were. Some threats give more score and some less as the system calcuates this. Hearts are a basic system in tower defense games, indicating after the threat passes what you have to defend which is the computer, you lose a heart. If the system detects all are depleted, the game would end.

**Outputs:**

- Visual feedback: Threats can be depicted as either 2D characters or 3D characters moving across a path from a birds eye view. Towers can also be depicted as the same 2D or 3D characters, and shoot projectiles to show they are functioning in containing the threats.

- Sound Effects: Sound effects for placing towers and attacks, game over screens, game success screens, threats being eliminated.

- Endgame Feedback: If all waves are passed or were failed to be passed, there will be a detailed report at the end of a stage to inform which threat breached the network (If it was breached), which units were effective, which units would be effective.

**Transmission:**

- Leaderboard for infinite waves: The game will send data to an online leaderboard if implemented for an infinite wave gamemode.

**Storage**

- Progression in levels and Scores: The game will store the player's progression in completed levels, and scores that were achieved. 

- Towers that are unlocked: As the user progresses through the game, they would've unlocked towers which are saved by the game.
***

### **Functional Requirements**

**User Interaction**

- Description: Players place, upgrade, and sell towers to defend against cyber threats, such as firewalls, antiviruses, and encryption. (Still coming up with names for the towers). Pausing and resuming the game is also another aspect of user interaction.

- Mechanics: Dragging and dropping with mouse, players drop these towers onto a grid in the game, each with unique attributes for each threat. By doing so, this will deplete some of the currency. Clicking on these same towers, a small UI pops up with upgrades, a description of the unit's stats, and sell button. Upgrading would deplete some currency and upgrade the unit, and selling would give back 50% of the unit's value along with upgrades. A pause button in the top right/left is also made, which if pressed would activate a small UI in the middle with options to exit or resume.

**Core Gameplay or Simulation Mechanics**

- Description: The core gameplay is to protect the base by strategically placing towers.

- Mechanics: Towers attack incoming threats automatically, utilising their range and attack speed as well as their predetermined unique attributes. In relation to this, threats also move automatically towards the players base. As the waves pass automatically through the system telling, eventually it will result in game over or success. Mechanics such as these automatically occur through the system in response to user interaction.

**Scoring and Feedback**

- Description: The game rewards players with score after neutralising threats depending on threat level. The game also gives endgame feedback.

- Mechanics: Score is awarded after each threat is defeated, depending on how dangerous the threat is, the more or less points are awarded. Endgame feedback provides which threat breached the network (If it was breached), which units were effective, which units would be effective, and other statistics.

**Level Progression and Unit Progression**

- Description: As players progress through the game, they unlock certain levels and units to enhance their capabilities in defending threats. Levels also get considerably harder.

- Mechanics: Players unlock new units after clearing levels, and as levels proceed to get harder they can use new units. Players must survive all waves to clear a level.

**Saving Game Progress**

- Description: The game saves progress at the end of each level, or players can press a button.

- Mechanics: The game saves player progress, including units and level progression. Scores that were also made in infinite mode or any other level mode are also saved.

**Enemy/Tower Types and Behaviours**

- Description: Enemies and Towers have certain types which allow some towers to be more effective towards certain enemies. Enemies, may have certain resistances due to these if the correct type is not used.

- Mechanics: As the game progresses, problems such as type advantages may occur which force the players to use other strategies. Additional abilities also apply to each tower and enemy.
***

### **Non-Functional Requirements**

**Performance Requirements**

- Description: The game should run smoothly without lag or delay. Multiple towers and enemies on screen should not be hindering any performance.

- Specifications: Levels should load in under 5 seconds, FPS should be at least 30, user interactions should not be delayed, overall automated gameplay should not be delayed.

**Usability Requirements**

- Description: The game should be beginner friendly, allowing players of any skill level to navigate it.

- Specifications: A tutorial section would help players to navigate the interface, which should be clear to show certain statistics and basic information.

**Scalability Requirements**

- Description: The game should allow for future expansion, such as including new levels, towers, enemies.

- Specifications: The game should support additional integration of tower types and enemy behaviours. Towers, also should support the same terminology. Game balancing overall, as levels progress is an important feature that must be looked to in order to have future expansion of the game.

**Security Requirements**

- Description: As the game takes leaderboard rankings, user data such as name should be protected.

- Specifications: If the game collects any player data, this should be encrypted during storage and transmission to a leaderboard.
***

### **Social and Ethical Issues**

**Definitions**

- Equity: Equity is the principle of fairness and justice in treatment, access, opportunity, and advancement for individuals. In our context of a game, we ensure that all players regardless of all abilities or backgrounds, have fair access to the game and can participate fully.

- Accessibility: Accessibility is the concept of whether a product or service can be used by everyone. These laws exist to people with disabilities, ensuring equity among individuals. In our context, this involves creating games that can be enjoyed by all players, so they can have equal opportunities to engage with the game.

**Accessibility**

- Consideration: Will your project be usable by people of all abilities?

- Analysis: Ensuring accessibility in a game is crucial for reaching a wider audience, and providing equity in an enjoyable experience. Features such as customizable controls, can accomodate players which have such disabilities in struggling with traditional controls, allowing everyone to enjoy the gameplay.

**Privacy and Data Protection**

- Consideration: Will your project collect user data?

- Analysis: The game collects data through usernames used in high scores, which is a priority to handle this data securely and transparently. Players should be informed that data is being collected through this system, and that using real life names is not a recommended idea. 

**Fairness and Representation**

- Consideration: Does your project avoid stereotypes or bias?

- The game strives to avoid stereotypes and bias in character represenatation and gameplay scenarios. Characters are derived from cyber themed cartoony designs, which have careful consideration ensuring that it does not create any harmful stereotypes related to gender, race, or culture. 

**Mental and Emotional Well-Being**

- Consideration: Could you game or simulation affect users' mental health?

- The design of the game is prioritizing the least amoung of violent content, due to a game being for children. This inturn, ensures a positive gaming experience, where the game strives to create an engaging and also uplifting atmosphere for all players.

**Cultural Sensitivities**

- Consideration: Could any content be offensive to different cultures?

- The game's content should be designed with cultural sensitivity in mind, by avoiding any themes, symbols, narratives and any other offensive material which may cause disarray to any players from diverse cultural backgrounds.
***
