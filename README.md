🐍 Snake-Water-Gun Game in C

This is a simple terminal-based implementation of the Snake-Water-Gun game in the C programming language. It's a fun game similar to Rock-Paper-Scissors.
🎮 Game Rules

    Snake drinks Water → Snake wins

    Water disables Gun → Water wins

    Gun kills Snake → Gun wins

    If both players choose the same, it's a Draw.

🧑‍💻 How to Play

    Run the program.

    Enter your choice when prompted:

        0 → Snake 🐍

        1 → Water 💧

        2 → Gun 🔫

    The computer randomly selects its move.

    The winner is displayed based on the rules above.

🖥️ Output Example

Choose 0 for Snake, 1 for water and 2 for Gun 
1
Computer chose 2
You win!

🛠️ How to Compile and Run
On Linux/macOS:

gcc snake_water_gun.c -o game
./game

On Windows (using cmd with GCC installed):

gcc snake_water_gun.c -o game.exe
game.exe

📁 File Structure

    snake_water_gun.c → Main source code

    README.md → Game instructions and info

📌 Notes

    The computer uses a random number generator to choose its move using rand() % 3.

    Randomness is seeded with time(0) for varying outcomes on each run.
