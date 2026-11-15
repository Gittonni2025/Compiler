# ⚡ Fast Flash Lang (Compiler / REPL Engine)

**Fast Flash Lang** is a lightweight, high-performance command-line REPL (Read-Eval-Print Loop) and execution engine built from scratch in pure **C**. It features an integrated lookup registry containing **100 instant execution utility functions** spanning mathematics, finance, health, physics, string manipulation, and everyday utilities.

---

## 🚀 Key Features
* **100 Built-in Executable Functions**: Instant calculations and utility tasks via a dynamic command lookup table.
* **Smart Argument Parsing**: Automatically normalizes commas and spaces (supports both `add 200, 50` and `add 200 50`).
* **Interactive REPL Interface**: Continuous command execution loop with built-in `help` and `exit` commands.
* **Zero External Dependencies**: Written entirely in standard C99/C11, compatible with GCC and Code::Blocks.

---

## 🛠️ Project Structure
```text
Fast-Flash-Lang/
│
├── main.c          # REPL interface and main program loop
├── fastflash.h     # Core execution engine containing all 100 functions & registry
└── README.md       # Project documentation


📋 Categories of Functions (100 Total)
Basic & Advanced Math: Add, sub, mul, div, pow, sqrt, factorial, GCD, LCM, log, etc.

Unit Conversions: Temperature, distance, weight, data storage (MB/GB).

Finance & Budget: Tips, discounts, VAT, split bills, simple/compound interest.

Health & Fitness: BMI, BMR, water intake, sleep cycles, ideal weight.

Geometry & Physics: Area, volume, force, kinetic energy, pressure, speed.

String & Text Processing: Word count, reverse text, uppercase/lowercase, palindrome check.

Utilities & Fun: Prime checker, random range generator, coin toss, dice roll, pomodoro planner.


⚙️ How to Build and Run
Open Code::Blocks (or any C IDE supporting GCC C99/C11).

Create a new Console Application project in C.

Place main.c and fastflash.h in the project directory.

Make sure your compiler flag is set to C99/C11 (-std=c11).

Press F9 to Build and Run.


Flash> add 200, 50
= 250

Flash> c2f 37
= 98.60 °F

Flash> bmi 70, 1.75
BMI: 22.86 (Normal)

Flash> help

