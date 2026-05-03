# 4x4 X O game (Tic-Tac-Toe) with AI (IDDFS)

An interactive Java-based Tic-Tac-Toe game featuring an intelligent AI opponent. The game is built using Java Swing for the graphical user interface and implements advanced search algorithms to provide a challenging experience.

##  Key Features

* **Customizable Setup:** Users can choose their preferred character (X or O) and select the difficulty level before starting.
* **Intelligent AI:** The opponent uses the **Iterative Deepening Depth-First Search (IDDFS)** combined with the Minimax algorithm to determine the best moves.
* **Variable Difficulty:** * **Easy:** Shallow search depth (Level 1).
    * **Medium:** Balanced search depth (Level 3).
    * **Hard:** Deep search (Level 6) for maximum challenge.
* **Input Validation:** Robust error handling using loops to ensure all game settings are properly selected before launch.

##  Technical Details

### AI Algorithm
The core of the AI is based on **IDDFS**, which allows the game to search for optimal moves efficiently within a specific time or depth limit. It evaluates board states using a heuristic scoring system:
* **Winning State:** +100 / -100
* **Strategic Advantage:** +10 / -10 (based on board positioning)

### GUI Framework
Developed using **Java Swing**, ensuring a responsive and interactive user experience. The setup phase utilizes `JOptionPane` with custom `DEFAULT_OPTION` buttons for seamless navigation.

##  How to Run

1.  Make sure you have **Java Runtime Environment (JRE)** installed.
2.  Open the terminal/command prompt.
3.  Navigate to the `dist` folder.
4.  Run the command:
    ```bash
    java -jar X_O.jar
    ```

##  Project Structure
* `src/`: Contains the Java source code.
* `X_O.java`: The main game logic and GUI frame.
* `Main`: Handles the initial setup and character selection.
# 4x4 Tic-Tac-Toe with AI (IDDFS)

An interactive Java-based Tic-Tac-Toe game featuring an intelligent AI opponent. The game is built using Java Swing for the graphical user interface and implements advanced search algorithms to provide a challenging experience.

##  Key Features

* **Customizable Setup:** Users can choose their preferred character (X or O) and select the difficulty level before starting.
* **Intelligent AI:** The opponent uses the **Iterative Deepening Depth-First Search (IDDFS)** combined with the Minimax algorithm to determine the best moves.
* **Variable Difficulty:** * **Easy:** Shallow search depth (Level 1).
    * **Medium:** Balanced search depth (Level 3).
    * **Hard:** Deep search (Level 6) for maximum challenge.
* **Input Validation:** Robust error handling using loops to ensure all game settings are properly selected before launch.

##  Technical Details

### AI Algorithm
The core of the AI is based on **IDDFS**, which allows the game to search for optimal moves efficiently within a specific time or depth limit. It evaluates board states using a heuristic scoring system:
* **Winning State:** +100 / -100
* **Strategic Advantage:** +10 / -10 (based on board positioning)

### GUI Framework
Developed using **Java Swing**, ensuring a responsive and interactive user experience. The setup phase utilizes `JOptionPane` with custom `DEFAULT_OPTION` buttons for seamless navigation.

##  How to Run

1.  Make sure you have **Java Runtime Environment (JRE)** installed.
2.  Open the terminal/command prompt.
3.  Navigate to the `dist` folder.
4.  Run the command:
    ```bash
    java -jar X_O_Game.jar
    ```

##  Project Structure
* `src/`: Contains the Java source code.
* `X_O.java`: The main game logic and GUI frame.
* `Main`: Handles the initial setup and character selection.
