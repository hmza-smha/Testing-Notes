# Software Testing

- You can not claim that your software is BUG-FREE
- Testing should start as early as possible in the software development life cycle

## What is Software Testing?

- Check if the system **Defect free**

Software Testing is a process used to identify the corretness, completeness and quality of developed computer software, includes a set of activites conducted with the intent of finding errors in software so that could be corrected before the product is released to the end users.

## why Testing is Importabt ?

Software Bugs can be expensive or even dangerous.

## How to test ?

Imagine you want to move a file from folder 'A' to folder 'B'. What problems maybe happen ?

1. Try to move the file when it is open
2. You don't have the perrmession to paste in folder 'B'
3. Folder 'B' capacity is full
4. Folder 'B' already has a file with the same name
5. etc...

## Unit Testing

- It also called component testing.
- It performed on standalone module to check wheather it is developed correctly.
- **Login Functunality**
  - Enter Valid ID, Password
  - Enter inValid ID, Password
  - Empty ID, Password
  - etc...
- Unit tests done by developers

## System Testing

- System Testing is concerbed with behavior of the system as a whole
- Unlike Integration testing, which focuses on data transfer amongst modules, system testing complete end to end scenarios, as the way a customer would use the system
- Functional & Non-Functional tested

## Acceptance Testing

- Done at client location by the client
- Check if the system meets the requirment, not to find the bugs

## Integration Testing

- Indivisual modules are compined and tested as a group
- Data transfer between the nodules is tested throughly
- Done By Testers

### Integration Testing Approaches

#### Big-Bang Tesing

Wait all modules to be developed

- Time Cinsuming
- Difficult to trace root cause of bugs

### Incremental Testing

Modules are tested as and when they are available

- Top-Down approach using `stub`
- Bottom-up approach using `driver`

## Sandwich Testing

Compination of Top-Down & Bottom-Up Incremantal approaches

## Smoke/Santy Testing

- To check critical functionalities of the system before its is accepted for major testing
- Sanity testing is quick and is non-exhaustive.
- Goal is not to find defects but to check system health

## Regression Testing

| No. | Content |
| :-: | :------ |
