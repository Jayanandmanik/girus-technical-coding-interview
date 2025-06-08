# Algorithm Practice Repository

This repository contains solutions and examples for six algorithmic problems, implemented in Java. Each solution is provided with clear comments in simple English and includes test cases.

## Table of Contents

1. [Sudoku Validator with Custom Zones](#sudoku-validator-with-custom-zones)
2. [Alien Dictionary](#alien-dictionary)
3. [Knights and Portals](#knights-and-portals)
4. [Bitwise Matching Pattern](#bitwise-matching-pattern)
5. [Matrix Islands with Diagonals](#matrix-islands-with-diagonals)
6. [Mini Interpreter](#mini-interpreter)

---

## 1. Sudoku Validator with Custom Zones

**File:** `SudokuValidatorWithCustomZones.java`

### Description

Validates a 9×9 Sudoku board for standard rules (rows, columns, 3×3 boxes) and additional custom zones of 9 cells each.

### Usage

```bash
javac SudokuValidatorWithCustomZones.java
java SudokuValidatorWithCustomZones
```

Custom zones can be defined in the `main` method as a list of cell coordinates.

---

## 2. Alien Dictionary

**File:** `AlienDictionary.java`

### Description

Given a sorted list of words in an alien language, determines the character order using topological sort on the precedence graph.

### Usage

```bash
javac AlienDictionary.java
java AlienDictionary
```

Test cases are provided in `main` with expected outputs.

---

## 3. Knights and Portals

**File:** `KnightsAndPortals.java`

### Description

Finds the shortest path in a grid from top-left to bottom-right, moving in four directions and allowing one teleport between any two empty cells.

### Usage

```bash
javac KnightsAndPortals.java
java KnightsAndPortals
```

Three test cases demonstrate no-move, teleport-only, and unreachable scenarios.

---

## 4. Bitwise Matching Pattern

**File:** `BitwiseMatchingPattern.java`

### Description

Given an integer `n`, computes the next larger integer with the same number of binary `1`s using bit manipulation techniques.

### Usage

```bash
javac BitwiseMatchingPattern.java
java BitwiseMatchingPattern
```

Example inputs and outputs are in the `main` method.

---

## 5. Matrix Islands with Diagonals

**File:** `MatrixIslands.java`

### Description

Counts the number of islands in a matrix of `0`s and `1`s, considering horizontal, vertical, and diagonal connections.

### Usage

```bash
javac MatrixIslands.java
java MatrixIslands
```

Several test cases illustrate one, two, and three island scenarios.

---

## 6. Mini Interpreter

**File:** `MiniInterpreter.java`

### Description

Simple interpreter supporting `let` variable declarations and `if` statements with conditions. Evaluates integer expressions and prints final variable states.

### Usage

```bash
javac MiniInterpreter.java
java MiniInterpreter
```

The example program demonstrates variable assignments, conditional blocks, and expression evaluation.

---

## Contributing

Feel free to submit pull requests or suggest improvements.

---

## License

This code is released under the MIT License.
