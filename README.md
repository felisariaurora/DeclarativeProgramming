# Declarative Programming Project – Gerrymandering (ASP + Python)

![University](https://img.shields.io/badge/University-University%20of%20Parma-blue)
![Course](https://img.shields.io/badge/Course-Declarative%20Programming-orange)
![Language](https://img.shields.io/badge/Language-ASP%20%2F%20Python-green)
![Solver](https://img.shields.io/badge/Solver-Clingo-red)

This project demonstrates the use of **Answer Set Programming (ASP)** to model and analyze **gerrymandering strategies** in grid-based electoral systems. 

The objective is to partition a voting region (represented as a 2D grid) into a fixed number of contiguous districts to **maximize the number of seats won** by a given political party.

---

## 📂 Repository Structure

The repository contains the following main components:

- **`benchmarks/`** Contains 100 benchmark instances in ASP format (`.lp`).

- **`imgs/`** Graphical results, plots, and heatmaps used in the report.

- **`report/`** PDF reports containing theoretical background and experimental analysis (English and Italian versions).

- **`test/`** Utility scripts for vote counting (`count_voters.py`) and debugging (`debug_districting.lp`).

- **`extra/`** Notebooks and study notes from the Declarative Programming course.

- **`political_districting.lp`** The main ASP encoding for the districting problem.

- **`generate_benchmarks.py`** Python script used to generate randomized benchmark instances.

- **`run_experiments_python.py`** Python script orchestrating the solver using Clingo.

- **`results_python.csv`** Output file collecting all experiment results.

---

## 📄 Reports & Documentation

Theoretical background, model structure, and experimental analysis are detailed in the project reports:

- 🇬🇧 [**report/GerrymanderingENG.pdf**](report/GerrymanderingENG.pdf) – English version
- 🇮🇹 [**report/GerrymanderingITV.pdf**](report/GerrymanderingITV.pdf) – Italian version

---

## 👥 Contacts

For inquiries or feedback regarding this project:

* **Aurora Felisari** - [aurora.felisari@studenti.unipr.it](mailto:aurora.felisari@studenti.unipr.it)
* **Claudio Bendini** - [claudio.bendini@studenti.unipr.it](mailto:claudio.bendini@studenti.unipr.it)

---

## 🎓 Project Context

This work was developed as part of the **Declarative Programming** course at the **University of Parma** to explore logic-based modeling and optimization using ASP and Python.
