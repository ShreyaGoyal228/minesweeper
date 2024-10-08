Minesweeper on Console 🕹️
===============


This is a simple minesweeper game that runs directly in the terminal. The project is implemented in C++.
The program is tested on Windows 11 and Linux.

**Rules are every number indicated the mines around it's boxes maximum 5.**
**Dont reveal the mine in which case you loose.**

Features
--------
1. **Gameplay**
- Enter r for reveal and f for flag. then define the cell's coordinates x y and hit enter.
- After that board is re printed and the reveal mine or number or 0.
- If all the mines are flaged you will win the game.
- If you step on a mine, You will loose.

2. **UI**
- A coordinated board is displayed.
- After that a prompt is Displayed to enter values of the move.
- 
For windows you can install MINGW
and run
```bash
g++ -o main minesweeper.cpp
