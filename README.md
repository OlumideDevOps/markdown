
# Mini Project: Control Flow in Linux Shell Scripting

This Mini project is to test my skill with **Linux shell scripting – control flow**.

## What is Control Flow?

This is a flow that directs the order in which commands or instructions are executed in a script. It’s like a decisional roadmap which directs the path to take based on certain conditions OR the number of times to visit / operate in a place.

Control flow in shell scripting is a tool for making decisions. They are backbone statements that give decisional texture in programming. These statements allow your script to decide what to do or how to proceed based on the conditions, loops or user inputs.

Bash and other shell interpreters provide control flow statements like the below:

1. if / else
2. For loops
3. While loops
4. Until loops

## Stage 1: If / Else

The below is the entire script that focuses on the `if / else`:

```bash
#!/bin/bash

read -p "Enter a number: " num
if [ $num -gt 0 ]; then
    echo "The number is positive."
elif [ $num -lt 0 ]; then
    echo "The number is negative."
else
    echo "The number is zero."
fi
```

I will start with testing `if` and gradually move to `else` and Stage 2.

### Steps

1. Create a file and name it `control_flow.sh`
2. Put this code and execute: `read -p "Enter a number: " num`

#### After Execution:

The script gives no output because it has no standard output instruction.

### Added Standard Output

This is the outcome:

(Example Output Here)

### Explanation of `if`

- `-gt` operator = greater than
- `$num` = number variable

The `(if)` statement in this script is saying "if the number is greater than 0", reply with "The number is positive."

#### Outcome:

(Example Output Here)

### `elif` Statement

This allows testing when the `if` condition is not met. For example: if a number is 10 display "positive", but if the number is less than 10 display "negative". The `elif` handles the second part.

#### Outcome:

(Example Output Here)

### Testing for Zero

Zero was not defined yet. When tested, I got a message.

I decided to test for zero myself.

#### Outcome of Zero Control Flow Conditional Test:

(Example Output Here)

---

## Stage 2: Loops

Loops are tools used for the auto-generation of output results or reports. They are used for repetitive tasks.

### Key Concepts

- **For**: Initiates the loop.
- **Items**: Variable holding value in each iteration.
- **In**: List of items to iterate over.
- **;**: Separates list from `do`. Optional if `do` is on next line.
- **Do**: Starts block of commands.
- **Done**: Ends the loop.

#### Example: For loop

For: This is for single command for multiple responses at once.

### Bash Script Configuration

(Example Script Here)

### Output of the Command

(Example Output Here)

### Counting Messages

(Example Output Here)

### Using While Loop

#### Error Encountered

(Description of Error)

Used Davina AI to resolve the issue. Another error was encountered; the script kept repeating.

#### After Davina Correction

Tried the suggested syntax.

Then modified it.

#### Changing `i` to `2` Without Updating Initial

Got an error.

#### Rewrote Script

Outcome:

(Example Output Here)

### C-Style Form in Scripting

Typed script and substituted `i` with `1`, which caused an error.

An engineer (Rilwan) in a blocker session assisted and advised me to focus on error messages as they often contain the solution.

Changed `1` back to `i`, then executed.

Got the desired message.

#### Modified Script

Outcome:

(Example Output Here)

---

## Conclusion

That concludes the Mini Project on shell scripting.
