# Quoridor 

I am a C++ beginner. The development of this game was entirely driven by a sudden impulse and a desire to improve my programming skills. The inspiration came from a video of a physical board game, which I found fascinating and wanted to digitalize. Later, I discovered that this game already existed in digital form under the name **Quoridor**. Currently, some parts of the project are still unpolished—especially the UI—but the core gameplay is mostly playable. There might be minor bugs in the pathfinding logic for valid player moves. Your understanding is greatly appreciated!

<img src="https://github.com/user-attachments/assets/4d1792de-d2ec-4e9c-beb5-cc24ac4e05d3" alt="游戏截图 1" width="30%" />


## Development Process

During development, I utilized **DeepSeek AI** to help solve repetitive problems and conceptual algorithms, which significantly shortened my development time and boosted efficiency. However, the core game logic and technical implementation were still achieved by myself through several days of work. Given my limited experience, some aspects might not have turned out exactly as expected; I appreciate your patience. The screenshot below shows an early development build before the improved art style was adopted:

<img src="https://github.com/user-attachments/assets/79b91668-735d-458c-b40d-3dbc263f422b" alt="游戏截图 2" width="50%" />


## Inspiration & Design

* The game's art style and design were inspired by [@quoridorstrategy].
* During development, I learned to use the **raylib** library to implement graphics and interaction logic.

## Game Rules

Quoridor is a two-player strategic board game where the objective is to be the first to reach the opponent's starting baseline.

### Game Objectives

* **Player 1 (White)**: Starts from the left border of the board and aims to reach the right border.
* **Player 2 (Black)**: Starts from the right border of the board and aims to reach the left border.

### Controls & Instructions

1. **Moving the Pawn**:
* Click on your pawn, then click on a highlighted square to move.
* Pawns can move one square horizontally or vertically (up, down, left, right).
* If an opponent's pawn blocks your path, you can jump over it (provided the square behind it is empty).


2. **Placing Walls**:
* Press the `Q` and `E` keys to toggle the wall direction (horizontal or vertical).
* Click on the text "BLACK" or "WHITE" to enter preview mode and place walls.
* Click on the board grids to place a wall.
* Walls block the opponent's movement, but you cannot completely block off their path to the goal.


3. **Winning Condition**:
* The first player to reach their respective target baseline wins!

<img src="https://github.com/user-attachments/assets/e6a51b92-387c-4e76-a182-bdc6c05a7521" alt="游戏截图 3" width="50%" />


## How to Run the Game

1. Download the latest release file (`quoridor-v1.0.0.zip`).
2. Extract the zip file.
3. Run `main.exe` to launch the game.

## Development Environment

* **Programming Language**: C++
* **Graphics Library**: raylib
* **Development Tool**: Visual Studio Code
* **AI Assistance**: DeepSeek (used for code optimization and solving certain technical issues)

## Known Issues

* As a beginner developer, minor bugs may still be present in the game.
* The UI is still being optimized, and some features might feel unpolished.

## Future Plans

* Optimize the UI for a better user experience.
* Fix known bugs and improve game stability.
* Implement an AI opponent mode.
* Add more game modes (e.g., time trials, multiplayer modes, etc.).

## Feedback & Support

If you encounter any issues during gameplay or have any suggestions, feel free to open an Issue on GitHub or contact me directly.

## Acknowledgments

* Thanks to [@quoridorstrategy] for the inspiration.
* Thanks to the raylib community for their incredible support.
* Thanks to the game creator [Mirko Marchesi].
* Thanks to the free audio resource platform [Mixkit](https://mixkit.co/free-sound-effects/click/) for the click sound effects.

---

**Have fun playing!**
