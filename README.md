Jackaroo Java Game

A strategic card game where players compete to move their marbles around the board using playing cards with special abilities.

GameFiles

Download the game files for the best experience:
GameFiles Download

Gameplay

Watch the gameplay demo:
Gameplay Video

Game Overview

Jackaroo is a multiplayer card game that combines strategy and luck. Players use a deck of playing cards to move their marbles around the board, with each card having unique abilities and movement rules.

Features

Multiplayer gameplay with support for human and AI players

Strategic card-based movement system

Special card abilities (Ace, King, Queen, Jack, etc.)

Unique marble movement mechanics

Western-themed game board and graphics

Interactive game interface

Card discard and draw mechanics

Safe zones and home zones for marbles

Card Abilities

Card

Ability

Ace

Field a marble from the Home Zone or move one marble 1 step forward

Two

Move one marble 2 steps forward

Three

Move one marble 3 steps forward

Four

Move one marble 4 steps backward

Five

Move any marble 5 steps forward

Six

Move one marble 6 steps forward

Seven

Move two marbles a total of 7 steps or one marble 7 steps forward

Eight

Move one marble 8 steps forward

Nine

Move one marble 9 steps forward

Ten

Discard a random card from next player or move 10 steps forward

Jack

Swap marbles or move 11 steps forward

Queen

Discard a random card from a random player or move 12 steps forward

King

Field a marble or move 13 steps forward (killing marbles in path)

Marble Burner

Send an opponent's marble home

Marble Saver

Move your marble to a random safe zone

Installation

IntelliJ IDEA

Extract zip file and open the project:

Go to File > Open... and select the project directory.

Ensure the correct JDK is set (JDK 11 or higher).

Set up JavaFX:

Download the JavaFX SDK from the Gluon JavaFX download page.

Extract the SDK to a directory on your computer.

Go to File > Project Structure... > Libraries and add the JavaFX lib directory.

Go to Run > Edit Configurations... and add the following VM options:

--module-path /path_to_javafx_lib --add-modules javafx.controls,javafx.fxml,javafx.media

Build and run:

Build: Build > Build Project

Run: Select the main class and click the run button.

Eclipse

Import zip file into Eclipse:

Go to File > Import... > Existing Projects into Workspace.

Select the zip file.

Set up JavaFX:

Download and extract the JavaFX SDK as above.

Go to Project > Properties > Java Build Path > Libraries > Modulepath > Add External JARs... and add all JARs from the JavaFX lib directory.

Go to Run > Run Configurations... and add VM options:

--module-path /path_to_javafx_lib --add-modules javafx.controls,javafx.fxml,javafx.media

Build and run:

Build: Right-click the project > Build Project

Run: Select the main class and click run.

Dependencies

JavaFX: Required for the UI. Download from the Gluon page.

JDK 11 or higher: Java Development Kit for building and running the game.

For more on setting up JavaFX, refer to the Bro Code JavaFX Playlist.

How to Play

Start the game and select the number of players

Each player receives a set of marbles and cards

On your turn:

Play a card from your hand

Use the card's ability to move marbles

Draw a new card

The first player to get all their marbles to the Safe Zone wins

Controls

Mouse Click: Select and play cards, interact with menu buttons

Select Marbles: Input the target cell index in the "Select Marbles" panel to choose which marble to move

Fielding Shortcut (f): Instantly field a marble when playing an Ace or King

Terminate Game (x): Exit the current session immediately

Technical Details

Core Technologies

Java Development: Built using Java 23

JavaFX Framework: Scene Builder, FXML, CSS styling, MediaPlayer, Graphics & Animation APIs

Architecture & Design Patterns

MVC: Model (game logic), View (JavaFX UI), Controller (event handling)

OOP: Inheritance, polymorphism, encapsulation, abstraction

Key Features Implementation

Exception Handling: Custom exceptions, input validation

Concurrency: Threads for AI, asynchronous events

Data Management: Serialization for game state, player stats tracking

UI/UX Components

Custom card and marble controls

Animations for card flips and marble moves

Responsive layouts and scaling

AI Implementation

State evaluation and strategic decision-making

Testing & QA

JUnit for unit tests

Integration and performance testing

Credits

Contributing

We welcome contributions to improve the Jackaroo game! Feel free to:

Submit bug reports or feature requests using the Issues tab

Fork the repository and open a Pull Request with your improvements

Please follow standard Java coding conventions and provide clear documentation for any new features.

If you're unsure where to start, feel free to reach out via the Contact section.

German University in Cairo (CSEN401 Department)

Game Development by

Zeyad Ahmed Elsawi

Mark Raymond Takla

Jonathan Maged Daksis

Aly Ahmed Aly

Contact

Mark: https://www.linkedin.com/in/mark-takla/

Zeyad: https://www.linkedin.com/in/zeyad-elsawi-0a0063284/

