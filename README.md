# CSCI1302-Final
## Project Concept: Pokémon Battle Simulator

### Overview
Create an application that allows users to simulate Pokémon battles. The app will let users select Pokémon, their moves, and simulate the outcome of a battle based on various factors like type matchups, abilities, and stats.

### How it Aligns with Requirements:

#### 1. Integration with Another API: 
Alongside the GraphQL-Pokemon API, you could integrate a weather API. The weather conditions could affect the battle outcomes, simulating real-life scenarios like rain boosting water-type moves or sunshine boosting fire-type moves.

#### 2. User Input and API Interactions:
* Users can select Pokémon, moves, and items.
* The first API call retrieves Pokémon stats, abilities, and moves.
* User input (selected Pokémon and moves) is used to formulate a second API call to the weather API, deciding battle conditions.

#### 3. Combining API Responses:
* Use Pokémon data to set up the battle parameters.
* Incorporate weather data to modify battle conditions and outcomes.

#### 4. Functional and Non-Functional Requirements:
* GUI with JavaFX: Interactive and user-friendly interface for selecting Pokémon and moves.
* Exception Handling: Manage potential errors in API calls or data processing.
* Adherence to Code Style and Environment Specifications: Develop according to the guidelines provided in the project description.

#### 5. Additional Features
* Leaderboard: Track and display user scores based on battle outcomes.
* Pokémon Library: Allow users to view detailed information about each Pokémon.
