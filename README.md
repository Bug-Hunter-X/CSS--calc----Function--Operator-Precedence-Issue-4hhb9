# CSS `calc()` Function: Operator Precedence Issue

This repository demonstrates a subtle but important issue related to operator precedence within CSS's `calc()` function. The example highlights the potential for unexpected results if the order of operations is not explicitly defined using parentheses.

## The Problem

The core issue revolves around the use of percentages and arithmetic operators within the `calc()` function.  Without proper use of parentheses, the browser's interpretation of the calculation's order might differ from what's intended.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the example with incorrect operator precedence.  Observe the resulting width of the `.container` element.
3. Open `bugSolution.css` to see the corrected code with the use of parentheses ensuring correct calculation order.

## Solution

The solution involves using parentheses to explicitly define the desired order of operations within the `calc()` function.