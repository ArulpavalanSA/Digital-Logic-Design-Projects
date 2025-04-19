🔐🧮 Digital Logic Design Projects – Function Calculator, 4-Bit Counter, and Digital Lock System

📂 Repository Description:
This repository contains the simulation and documentation of three digital logic design projects completed as part of my preliminary induction tasks. All circuits are designed using digital logic components like logic gates, adders, multiplexers, and flip-flops. Simulation was done using Digital Logic Sim by Sebastian Lague /Multisim.

🧠 Projects Included:
1️⃣ 4-Function Calculator (4-bit Inputs)
Performs Addition, Subtraction, Multiplication, and Division.

Operates on two 4-bit binary numbers (AAAA and BBBB).

Uses ripple-carry adder, 2’s complement subtractor, combinational multiplier, and basic divider logic.

Control bits (2-bit) select the operation:
00 → Add, 01 → Sub, 10 → Mul, 11 → Div.

Overflow indicator and division-by-zero handling included.

Output can be 4-bit or 8-bit, depending on operation.

2️⃣ 4-Bit Binary Counter
Built using T (or D/JK) flip-flops.

Counts from 0000 to 1111 and wraps back to 0000.

Includes a reset button to bring count to zero.

Optional Up/Down mode controlled via toggle bit.

Clocked using a stable pulse generator or debounced push button.

3️⃣ 4-Bit Digital Lock System
Compares user input (via switches/buttons) with a preset code: 1110.

Uses XOR and AND gates for bitwise comparison.

Lights up “Unlocked” LED on successful match.

Optional features: Reset signal or lockout on multiple wrong attempts.

📎 Files Included:
.mp4 video explanation of all three tasks

.docx documentation with block diagrams, truth tables, circuit explanation

Project simulation files (depending on the tool used)

📚 Tools & Resources Used:
Digital Logic Sim by Sebastian Lague / Proteus / Multisim

Flip-flop and ALU design resources

GFG articles, YouTube tutorials, Digital Logic Design book

🚀 Highlights:
Clean and modular circuit design

Clear step-by-step explanation in both video and document

Brownie-point features implemented like overflow indicator, reset logic, and extra security in digital lock
