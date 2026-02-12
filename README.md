#  Indian Engineer Ultimate (V.2026)
### *High-Fidelity Scientific Calculator Simulation*

Developed by **Sai Keerthi**, this project is a robust, web-based emulation of the classic scientific calculators used by engineering students. It blends nostalgia with a modern "Dark Mode" aesthetic and specialized computation modes.

---

##  Live Demo
Experience the "Indian Engineer Ultimate" here:  
👉 **[keerthi-padamati.github.io/Basic_Engineering_Casio/](https://keerthi-padamati.github.io/Basic_Engineering_Casio/)**

---

##  Key Modules
The project uses a dynamic rendering system to switch between specialized engineering modes:

* **COMP (Computation):** General arithmetic with trigonometry (degrees), logarithms, and square roots.
* **MAT (Matrix):** Automated $2 \times 2$ Determinant calculation with instant result display.
* **EQN (Equation):** Quadratic root solver ($ax^2 + bx + c = 0$) that handles both real and imaginary error states.
* **STAT (Statistics):** Quick processing for Mean and Variance of comma-separated data sets.
* **BASE (Base-N):** Instant Decimal to Binary and Hexadecimal conversion.
* **CONST (Constants):** One-tap access to physical constants:
    * Speed of Light ($c$)
    * Planck's Constant ($h$)
    * Gravity ($g$)
    * Electron Charge ($e^-$)

---

##  Design Features
* **Tactile Feedback:** Integrated Vibration API for a physical "click" feel on mobile devices.
* **LCD Simulation:** Custom CSS dot-matrix background pattern for an authentic hardware display feel.
* **Solar Strip UI:** Accurate visual representation of the Casio solar panel array.
* **Tricolor Accents:** Saffron and Green button themes paying homage to the "Indian Engineer" edition branding.
* **Responsive Chassis:** Optimized for both mobile vertical use and desktop screens.

---

##  Technical Stack
* **HTML5:** Semantic structure and LCD display mapping.
* **CSS3:** Custom variables, grid layouts, and 145° linear gradients for the "chassis" depth.
* **JavaScript (ES6):** Logic for mathematical parsing, mode switching, and haptic response.

---

##  Project Structure
```bash
├── index.html   # Calculator structure & UI components
├── style.css    # Engineering aesthetics & layout
└── script.js    # Computational logic & mode management
