### Lox Programming Language

Lox is a simple, dynamically typed scripting language created by Bob Nystrom in Crafting Interpreters to teach compiler and interpreter design.

## Features

- Dynamically typed language.
- Supports classes with single inheritance.
- First-class functions with closures.
- Lexical scoping with nested blocks.
- Primitive types: number, string, boolean, and nil.
- Control flow with if, else, while, and for.
- Arithmetic, comparison, and logical operators.
- String concatenation using the + operator.
- Minimal standard library with functions like print().
- Objects and methods resolved using dynamic dispatch.

## Example Code

```python
class Doughnut {
    cook() {
        print "Fry until golden brown.";
    }
}
class BostonCream < Doughnut {
    cook() {
        super.cook();
        print "Pipe full of custard and coat with chocolate.";
    }
}
BostonCream().cook();
```
