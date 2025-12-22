# CLAC — Console Logic And Calculation (Windows C)

A clean, menu‑driven console app that brings everyday conversions and scientific calculations into one place.  
Built in C for Windows (MinGW + Code::Blocks IITB edition), with smooth text animations, colored output, and persistent history.

---

## ✨ Features
- Temperature converter: Celsius, Fahrenheit, Kelvin
- Unit converter: Length, Mass, Time, Speed, Energy/Power
- Currency converter: INR, USD, EUR, GBP, JPY (static rates)
- Scientific calculator: Everyday math, logs, factorial, powers, roots, trigonometry
- Console UX: Animated banners, color themes, cursor control, ASCII art screens
- History tracking: Separate histories for conversions and calculations

---

## ⚙️ Build Instructions (MinGW + Code::Blocks)

### Using Code::Blocks IITB
1. Open Code::Blocks.
2. File → New → Empty File → Save as `main.c`.
3. Paste the CLAC source code.
4. Press **F9** (Build & Run).

### Using MinGW directly
```bash
gcc -o clac.exe main.c -luser32 -lkernel32 -lshell32
./clac.exe
