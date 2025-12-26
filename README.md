Open the zip file and run the roll.java to start the game, you can choose difficulty levels from easy to tricky. 
# Cache Noisette (Java Swing Mini-Game)

A small **Java Swing** GUI mini-game built as an independent project.  
It includes multiple difficulty levels and grid-based movement controls.

> Entry point: `Roll.java` (contains `public static void main(String[] args)`)

## Features
- Java Swing GUI (levels, buttons, Squirrels)
- Multiple difficulty levels (e.g., Easy / Medium / Hard / Tricky)
- Grid-based gameplay with movement controls
- Basic game state handling (reset / win conditions)

## Requirements
- **JDK 11+** (JDK 17+ also works)

Check your Java installation:
```bash
java -versions
javac -version

## How to run
From the folder containing Roll.java and other .java files:
javac *.java
java Roll
Note: Remember to tab its head before controlling its movement with arrows.

## Project Structure
	•	Roll.java — GUI entry + main window
	•	Easy.java, Medium.java, hard.java, tricky.java — level logic (coursework style)
	•	Grid.java, Arrows.java, Squirrel.java, etc. — game objects / helpers

 
