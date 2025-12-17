Bomberman Classic Remake
A local multiplayer recreation of the classic Bomberman game built in Unity. Two players share the same keyboard and battle in a maze full of destructible blocks, enemies, and power-ups.

Features
Classic Bomberman-style grid movement, bomb placing, and cross-shaped explosions.​

Local 2‑player versus mode on a single screen.

Destructible and indestructible blocks that shape the arena.

Power-ups that modify bomb count, explosion range, and movement speed (update based on your implementation).

Simple, fast-paced matches ideal for quick local battles.

Local Multiplayer
The game is designed for two players on one keyboard:

Both players are visible at the same time, each starting on opposite sides of the arena.

Friendly fire is possible if a player is caught in any explosion, including their own bombs.

Last player standing wins the round (or define your own win condition here).

Controls
Player 1 – Right side of screen

Move Up: W

Move Left: A

Move Down: S

Move Right: D

Place Bomb: Space

Player 2 – Left side of screen

Movement: Arrow keys (↑, ↓, ←, →)

Place Bomb: 0 key (on the main keyboard row, or specify numpad if that’s what you use)

Update this section if you support remapping or gamepads.

How to Play
Navigate the maze, place bombs to destroy soft blocks, and open new paths.

Try to trap your opponent or push them into risky positions using bomb timing and positioning.

Collect power-ups from destroyed blocks to gain an advantage.

Avoid explosions from both your own bombs and your opponent’s bombs.

Installation & Setup
Clone the repository:

bash
git clone https://github.com/<your-username>/<your-repo-name>.git
Open the project in Unity (version: 20XX.X – replace with your actual version).

Open the main scene (for example Assets/Scenes/Main.unity).

Press Play in the Unity Editor to start a 2‑player match.

To create a standalone build:

Go to File → Build Settings.

Add your main scene to the build list.

Select your target platform (e.g. Windows).

Click Build and run the generated executable.

Project Structure
Assets/Scripts – Player movement, bombs, explosions, game manager, power-ups, and multiplayer logic.

Assets/Prefabs – Players, blocks, bombs, power-ups, and level tiles.

Assets/Scenes – Game scenes (main menu, arena, etc.).

Assets/Art / Assets/Sprites / Assets/Models – Visual assets.

Assets/Audio – Music and sound effects.

Known Issues / Future Work
Optional: list bugs (e.g. edge cases with collisions or input).

Possible improvements: more maps, more power-ups, score system, round-based matches, 3–4 player support, controller support.

Disclaimer
This project is a fan-made educational remake and is not affiliated with or endorsed by the creators or rights holders of the original Bomberman series.
