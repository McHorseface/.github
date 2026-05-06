# Joshua's Learning Resources

A curated learning plan for Joshua — covering JavaScript, Python, C++, React, Electrical Engineering, and Math. Built to complement his path into Electrical Engineering in college.

---

## 🗺️ Big Picture First

Before diving in, start here to understand the full EE degree roadmap:

- [McHorseface/OSEE](https://github.com/McHorseface/OSEE) — Open-Source EE Degree: maps out a full EE bachelor's by semester with textbook and course recommendations
- [McHorseface/BSc-electrical-engineering](https://github.com/McHorseface/BSc-electrical-engineering) — One student's complete BSc EE summaries and notes — useful preview of what's coming
- [McHorseface/mathematics-roadmap](https://github.com/McHorseface/mathematics-roadmap) — Visual roadmap from basic math through calculus, linear algebra, and differential equations

---

## The Plan (4 Steps)

### Step 1 — Embedded "Hello World" with Arduino (2–3 weeks)
Learn C/C++ in context by wiring up real hardware: button + LED + sensor.

**Repos:**
- [McHorseface/beginner-arduino-projects](https://github.com/McHorseface/beginner-arduino-projects) — LED blink, button LED, traffic light, temperature monitor
- [McHorseface/Beginner-Kit-for-Arduino](https://github.com/McHorseface/Beginner-Kit-for-Arduino) — Kit lesson series with sample code

**Why:** Connects code to real circuits — exactly what EE students work with in embedded systems courses.

---

### Step 2 — Learn Python for Engineering (4–6 weeks)
Focus on NumPy, Matplotlib, SciPy, and Jupyter notebooks applied to EE problems.

**Repos:**
- [McHorseface/Electrical-Engineering-with-Python](https://github.com/McHorseface/Electrical-Engineering-with-Python) — Circuit analysis and simulations using NumPy/SciPy/Matplotlib
- [McHorseface/ElectricPy](https://github.com/McHorseface/ElectricPy) — Python library of EE functions for circuits and machines

**Why:** Python is the "glue" language of EE — used for data analysis, simulation, lab automation, and signal processing.

---

### Step 3 — Sensor Data Logging & Analysis (2–3 weeks)
Extend the Arduino project to send data to a PC, then analyze and plot it in Python.

**How:**
1. Arduino logs sensor readings over serial
2. Python script captures, cleans, and plots the data
3. Use notebooks from `Electrical-Engineering-with-Python` as a style guide

**Why:** End-to-end pipeline — hardware → data collection → analysis — mirrors real EE workflows.

---

### Step 4 — Simple JS/React Dashboard (3–4 weeks)
Build a basic web dashboard to display sensor data using existing JavaScript skills.

**Repos:**
- [McHorseface/react-vis](https://github.com/McHorseface/react-vis) — Data visualization components for React
- [McHorseface/reaviz](https://github.com/McHorseface/reaviz) — Modular React data viz components

**Why:** Reuses JavaScript skills to present real engineering data, instead of learning web frameworks in isolation.

---

## 🔢 Math (follow this sequence)

Math is the backbone of EE. Here's the sequence Joshua will follow and the repos to go with each course.

| Course | When | Repos |
|---|---|---|
| Calc 1 | Year 1, Fall | Calculus-Guide, mathematics-roadmap |
| Calc 2 | Year 1, Spring | Calculus-Guide |
| Diff Eq | Year 2 | Differential-Equations-Guide, diff-eqs-eng-ru |
| Linear Algebra | Year 2 | linalg-diffeq |

- [McHorseface/Calculus-Guide](https://github.com/McHorseface/Calculus-Guide) ⭐ **Start here for Calc 1 & 2** — Formulas, theorems, and practical applications for calculus
- [McHorseface/mathematics-roadmap](https://github.com/McHorseface/mathematics-roadmap) — Visual roadmap showing how all the math connects from arithmetic through advanced topics
- [McHorseface/Differential-Equations-Guide](https://github.com/McHorseface/Differential-Equations-Guide) — Diff eq reference guide (circuits and signals live here — this math is everywhere in EE)
- [McHorseface/diff-eqs-eng-ru](https://github.com/McHorseface/diff-eqs-eng-ru) — Free textbook: *Differential Equations: An Introduction for Engineers*
- [McHorseface/linalg-diffeq](https://github.com/McHorseface/linalg-diffeq) — Actual college course materials for Linear Algebra + Differential Equations

> **Pro tip:** Differential equations will show up constantly in EE — RC circuits, signal processing, control systems. The earlier Joshua gets comfortable with them the better.

---

## ⚡ First-Year EE Undergrad Resources

These map directly onto what you'll see in your first year of EE coursework.

- [McHorseface/DC-Circuit-Analysis](https://github.com/McHorseface/DC-Circuit-Analysis) ⭐ **Most relevant** — Interactive MATLAB live scripts covering mesh analysis, nodal analysis, Thevenin circuits, RL/RLC circuits, and op amps. Mirrors your first circuits course.
- [McHorseface/EE-Resources](https://github.com/McHorseface/EE-Resources) — Curated list of resources for EE students including embedded programming
- [McHorseface/awesome-electronic-engineering](https://github.com/McHorseface/awesome-electronic-engineering) — Circuit simulators, embedded systems, components, and learning resources

> **Note on MATLAB:** It shows up heavily in EE coursework (especially circuits and signals). It's paid software, but your university will almost certainly give you free access once you're enrolled.

---

## C++ Learning Repos

- [McHorseface/CPP_Beginner_to_Expert](https://github.com/McHorseface/CPP_Beginner_to_Expert) ⭐ **Start here** — Basic to advanced, heavily commented
- [McHorseface/CPP-Guide](https://github.com/McHorseface/CPP-Guide) — Modern C++ quick reference (use after basics are solid)
- [McHorseface/C-CPP-Programming](https://github.com/McHorseface/C-CPP-Programming) — Beginner C/C++ projects
- [McHorseface/Modern-CPP-Programming](https://github.com/McHorseface/Modern-CPP-Programming) — Modern C++ course covering C++03 through C++26

---

## Python Learning Repos

- [McHorseface/30-Days-Of-Python](https://github.com/McHorseface/30-Days-Of-Python) ⭐ **Start here** — 30 days of structured, incremental exercises
- [McHorseface/Python-programming-exercises](https://github.com/McHorseface/Python-programming-exercises) — 100+ challenging Python exercises
- [McHorseface/python-guide](https://github.com/McHorseface/python-guide) — Python best practices guidebook
- [McHorseface/Amazing-Python-Scripts](https://github.com/McHorseface/Amazing-Python-Scripts) — Curated Python scripts from basics to advanced
- [McHorseface/PythonAlgorithms](https://github.com/McHorseface/PythonAlgorithms) — Algorithms implemented in Python
- [McHorseface/awesome-python](https://github.com/McHorseface/awesome-python) — Curated list of Python frameworks, libraries, and tools
- [McHorseface/100-Days-Of-ML-Code](https://github.com/McHorseface/100-Days-Of-ML-Code) — 100 days of ML coding (for later, once Python basics are solid)

---

## React / JavaScript Learning Repos

- [McHorseface/reactjs_koans](https://github.com/McHorseface/reactjs_koans) ⭐ **Start here** — Fix failing tests to learn React (great if you already know JS)
- [McHorseface/awesome-react](https://github.com/McHorseface/awesome-react) — Curated React ecosystem resources
- [McHorseface/awesome-javascript](https://github.com/McHorseface/awesome-javascript) — Curated JavaScript libraries and resources

---

## Recommended Reading

- [From Electrical Engineering to Data Science: What I Wish I Knew Earlier](https://python.plainenglish.io/from-electrical-engineering-to-data-science-what-i-wish-i-knew-earlier-5a66008a8072) — Hamaylshah, Python in Plain English

---

## A Note on C++

C++ is NOT a waste of time for EE. For general app development it can be overkill — but for microcontrollers, embedded systems, and firmware, C/C++ is the standard. Arduino itself is written in C/C++. If you ever write firmware or talk close to the hardware, this is the language you'll use.
