# Success Criteria Checklist

This checklist can be used to gauge progress towards different levels of success. Note that to pass, *all* of the Achieve Criteria must be met; for Merit, you need all Achieve, plus all the Merit Criteria, and so on for Excellence too.

---

## Achieve Criteria

### Program Functionality

The game functions correctly and meets the specification:
- [ ] The game is playable
- [ ] The game has a GUI
- [ ] The instructions for the game are available via the GUI
- [ ] Player provides inputs to the game via the GUI (e.g. moves, actions)
- [ ] The current state of the game is shown in the GUI after each player input
- [ ] The player can move between multiple locations
- [ ] The player has a clear purpose they can attempt to achieve
- [ ] A win / end / loss state is possible

### Program Code

The program stores data using:
- [ ] **Variables** of at least two types (e.g. int, text, boolean)

The program structure:
- [ ] Makes use of user-defined OOP **classes** from which **objects** are instantiated
- [ ] Uses **functions** / **methods** to break up the code logically
- [ ] Contains **sequences** of instructions
- [ ] Uses **conditional** instructions to control the program flow
- [ ] Uses program **branches** (if...else, when, etc.)
- [ ] Uses **iteration** (loops) to repeat things (for, while, etc.)

[//]: # (TODO: FINISH THIS!)

### Program Documentation

The program code:
- [ ] Is **indented** correctly
- [ ] Is **laid-out clearly**
- [ ] Contains **comments** that help in understanding how it works

### Program Testing

The program has been tested and there is documented evidence that:
- [ ] The game is **fully functional**, showing testing of:
  - [ ] game setup
  - [ ] player moves
  - [ ] players taking turns
  - [ ] scoring (if any)
  - [ ] players winning
  - [ ] final feedback (if appropriate)
- [ ] **Valid (expected) data** has been used to test **all data inputs**
- [ ] Where tests have failed, **fixes** are discussed and **tests re-run**

---

## Merit Criteria

### Program Code

The program stores data using variables, where:
- [ ] They are **scoped appropriately** (global or local to a function)
- [ ] **Global** variables are only used if **genuinely needed**
- [ ] Variable **names are well-chosen** (relating to their purpose) 

The program uses functions appropriately, where:
- [ ] The function **names are well-chosen**, relating to their functionality 
- [ ] Has at least one function that uses **parameters** to pass data into it
- [ ] Has at least one function provides a **return value** to the calling code

### Program Documentation

The program code comments:
- [ ] Accurately describe the **function and behaviour** of the code:
  - [ ] Defining the **purpose** of functions / key blocks of code
  - [ ] Explaining the **reason** (the '**why**') of key parts of the code
  - [ ] Defining function **parameters** and/or **return values**

### Program Testing

The program has been tested using:
- [ ] A test plan **prepared in advance** of the coding
- [ ] A test plan that **defines test data values** to be used
- [ ] Test values that cover **boundary** (limit / edge) cases

---

## Excellence Criteria

### Program Code

Program flexibility and maintainability is aided by:
- [ ] **Constants** being used to define key values, and used throughout the program
- [ ] Variable values being **derived at run-time** (from other variables / constants)
- [ ] Literal values only being used if they **make sense**, and they don't impact program flexibility

Program flexibility and maintainability is aided by good program structure:
- [ ] Conditions, branching, loops and functions are used **effectively**
- [ ] Procedures are **efficient** (minimal iterations, etc.)
- [ ] **Minimal duplication of code** (instead using loops, or having multiple calls to a single function)
- [ ] Functions are **well-chosen and logical**, with a clearly defined purpose

### Program Documentation

The program code:
- [ ] Code is laid-out and organised **logically and concisely**

### Program Testing

The program has been tested to be **robust**:
- [ ] With a **comprehensive and thorough** test plan
- [ ] Testing **regularly** throughput development, allowing **time for debugging**
- [ ] Using test values that cover **invalid** (unexpected) cases
- [ ] Resulting in a program that **copes appropriately** with invalid inputs
