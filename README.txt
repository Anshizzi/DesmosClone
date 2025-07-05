# Desmos Clone - Java Function Plotter

This project is a Java-based desktop application that replicates core features of the Desmos graphing calculator. Built using the Java Swing framework, it enables users to visually plot a wide range of mathematical functions with customizable parameters.

---

## Features

* Plot common functions such as:

  * sin(x), cos(x), tan(x)
  * Polynomial functions like x², x³
  * Linear functions (e.g., 2x + 3)
  * log(x), exp(x), step(x)
* Adjustable parameters to scale function output
* Background color selection using a color picker
* Ability to clear the graph panel

---

## Folder Structure

```
ProjectTupperware/
├── src/
│   ├── Main.java
│   ├── ui/
│   │   └── DesmosCloneApp.java
│   └── util/
│       └── [helper classes, if any]
```

---

## Compilation and Execution

### Compile

Ensure you are in the root directory of the project. Then compile using the following command:

```bash
javac -d . src/Main.java src/ui/*.java src/util/*.java
```

### Run

```bash
java src.Main
```

---

## Requirements

* JDK 8 or higher
* A terminal or IDE configured with the Java Development Kit

---
