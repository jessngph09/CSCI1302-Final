# Screen Layout_Setting up JavaFX

## Layout Design:
* Use a BorderPane as the root layout.
* Top section: Menu or buttons for general app controls.
* Left section: Pokémon selection area with ListView or custom components for displaying Pokémon and their stats.
* Center: Battle simulation area. Use a Pane or AnchorPane for flexible placement of Pokémon images and battle animations.
* Right section: Educational sidebar. A VBox with Labels or a WebView for displaying type effectiveness information.
* Bottom: Results panel. A TextArea to display battle outcomes and details.

## Styling:
* Use CSS for styling your components to match the Pokémon theme.
* Set background images, fonts, and color schemes that align with the visual concept.

## Interactive Elements:
* Implement buttons with action handlers for selecting Pokémon and moves.
* Add event listeners to update the battle simulation and results based on user choices.

## Pokémon and Moves Selection:
* Populate the Pokémon selection area with data fetched from the API.
* Allow users to choose moves and see the effects on the battle simulation.
  
## Battle Simulation Logic:
* Implement the logic to simulate battles based on Pokémon stats, moves, and type effectiveness.
* Update the central area to reflect the ongoing battle, showing animations or changes in Pokémon status.

## Educational Sidebar:
* Use the Type Effectiveness API to provide useful information to the user.
* Display this information in an accessible and easy-to-understand format.

## Results Display:
* After each simulated battle, show detailed results in the bottom panel.
* Include information like damage dealt, effectiveness of moves, and the winner.

## Testing and Refinement:
* Continuously test each component and refine the app for better performance and user experience.
* Ensure that the app is responsive and functions as expected.
