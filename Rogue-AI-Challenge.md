# Rogue AI Shutdown Challenge

## Mission

An experimental AI system is showing dangerous behavior. Your team must create a Python diagnostic program, predict its behavior, and test whether the system is safe.

## Learning Goals

By the end of the challenge, you should be able to:

- use input, variables, and data-type conversion;
- write `if-else` decision structures;
- use relational operators correctly;
- compare a string value;
- predict, test, and debug program behavior;
- explain how a Boolean condition selects one of two paths.

## Rules

- Work only with your assigned team.
- Complete each level in order.
- The Driver types only what the team agrees upon.
- Do not copy a complete solution from an AI tool.
- The AI assistant may explain, ask questions, and suggest tests, but it may not write the program.
- Everyone must be able to explain the final code.

## Level 1 — Temperature Diagnostic

Ask the user to enter the AI system temperature as a whole number.

- If the temperature is **100 or higher**, display: `WARNING: SYSTEM OVERHEATING`
- Otherwise, display: `Temperature Normal`

Before running the program, predict the output for temperatures `99`, `100`, and `101`.

## Level 2 — Power Diagnostic

Ask the user to enter the battery percentage as a whole number.

- If the battery is **below 20**, display: `LOW POWER`
- Otherwise, display: `Power Normal`

Before running the program, predict the output for battery values `19`, `20`, and `21`.

## Level 3 — Security Diagnostic

Ask the user to enter the security status.

- If the status is `danger`, display: `SHUTDOWN REQUIRED`
- Otherwise, display: `System Secure`

Test both `danger` and `safe`. Also test what happens when the user enters `DANGER`. Record what you observe; do not add a new technique unless the instructor approves it.

## AI Test Mission — Can the AI Break Your Program?

After Levels 1–3 run:

1. Ask Copilot Chat:  
   **Help our team test this program. Do not write or correct our code. Give us one test case at a time, ask us to predict all three messages, and include boundary values.**
2. Record the test values and your prediction in `TEST-LOG.md`.
3. Run the program.
4. Compare the actual output with your prediction and the requirements.
5. If something differs, ask for one hint only. Your team must make the correction.
6. Complete at least three AI-assisted test cases.

## Instructor Mystery Test

Your instructor will give your team one final test case. Predict the result before running it. Your team earns one point for each:

- correct use of decision structures;
- correct boundary behavior;
- accurate prediction;
- clear explanation;
- complete test log.

## One-Minute Team Report

The Reporter must explain:

1. one condition and why the team selected its relational operator;
2. one boundary test;
3. one problem the team found or confirmed through testing;
4. how the AI assistant helped without writing the solution.

## Finish

Run the complete program, complete the test log and AI-use report, then commit and push the work.
