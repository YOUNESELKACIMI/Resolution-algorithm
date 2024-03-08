# Resolution Algorithm for Logical Inference

This repository contains an implementation of the Resolution Algorithm for logical inference. The Resolution Algorithm is a fundamental method in automated reasoning and logic, used to check the validity of logical statements in propositional logic.

## Table of Contents

- [Overview](#overview)
- [How it Works](#how-it-works)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Resolution Algorithm is a decision procedure for checking the validity of a first-order logic formula by refutation. It operates by trying to find a contradiction from the set of clauses obtained by converting the input formula into conjunctive normal form (CNF).

This repository provides a Python implementation of the Resolution Algorithm, allowing users to input logical expressions and determine their validity.

## How it Works

The main steps of the Resolution Algorithm implementation are as follows:

1. **Conversion to CNF**: The input logical expression is converted into Conjunctive Normal Form (CNF) using the `to_cnf` function from the `sympy` library.

2. **Negation and Simplification**: The CNF form of the negated input expression is generated, and then simplified using `to_cnf` again.

3. **Resolution**: The algorithm performs resolution on the set of clauses obtained from the negated and simplified CNF.

4. **Validity Check**: If an empty clause (contradiction) is derived, the original formula is considered valid.

## Usage

To use the Resolution Algorithm:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/resolution-algorithm.git
