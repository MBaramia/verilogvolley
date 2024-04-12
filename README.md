**FPGA Ping Pong Game**

**Description:**
This project implements a classic ping pong game on an FPGA board using Verilog. It utilizes hardware descriptive language to design the game logic, including finite state machines, sequential and combinational logic, pipelining, and timing constraints. Players control paddles to bounce a ball back and forth, aiming to prevent it from passing their side of the screen. The game features interactive gameplay and scoring, providing an engaging experience for users.

**Features:**
1. Classic ping pong gameplay.
2. Real-time paddle control using buttons.
3. Collision detection and ball movement.
4. Score tracking and display.
5. VGA output for graphics rendering.
6. Finite state machines for game state management.
7. Sequential and combinational logic for game mechanics.
8. Pipelining for efficient data processing.
9. Timing constraints to ensure smooth gameplay.
10. Reset functionality for restarting the game.

**Requirements:**
- FPGA board with VGA output support.
- Software toolchain for FPGA development (e.g., Xilinx Vivado).
- Basic understanding of Verilog hardware descriptive language.
- USB cable for programming the FPGA board.

**Installation:**
1. Connect the FPGA board to your computer via USB.
2. Open the project in your FPGA development environment.
3. Compile the Verilog code and program the FPGA board.
4. Connect the FPGA board to a VGA monitor.
5. Power on the FPGA board and start playing the game.

**Usage:**
- Use the UP and DOWN buttons to control the paddle's movement.
- Keep the ball bouncing between the paddles to prevent it from passing your side.
- Score points for each successful bounce.
- The game ends when the ball passes beyond your paddle, triggering a game over screen.
- Press the RESET button to restart the game.
