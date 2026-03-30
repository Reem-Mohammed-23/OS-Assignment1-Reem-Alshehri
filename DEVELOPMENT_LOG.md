# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

### Entry 1 - [March 28 , 2026, 3:30 PM]
**What I did**: Forked the repository and set up the project


**Details**: 
- Created a fork of the assignment repository
- Opened the project in my IDE
- Reviewed the provided code structure
- Ran the program for the first time


**Challenges**: 
Understanding the overall structure of the code and how threads are used

**Solution**: 
Carefully read the code and traced execution step-by-step

**Time spent**: 1 hour


---

### Entry 2 - [March 28, 2026, 5:00 PM]
**What I did**: Added student ID and tested randomness

**Details**: 
- Inserted my student ID into the random generator
- Observed changes in number of processes and burst times
- Verified that output is unique

**Challenges**: 
Understanding how Random with seed works
**Solution**: 
Researched how seeded randomness ensures consistent but unique output

**Time spent**: 
45 minutes
---

### Entry 3 - [March 29, 2026, 2:00 PM]
**What I did**: Implemented Feature 1 (Priority)

**Details**: - Added priority variable to Process class
- Generated random priority (1-5)
- Displayed priority in ready queue output

**Challenges**: 
Priority was not showing initially
**Solution**: 
Fixed printing statement in addProcessToQueue method


**Time spent**:  1 hour

---

### Entry 4 - [March 29, 2026, 6:00 PM]
**What I did**:  Implemented Feature 2 (Context Switch)

**Details**: - Added counter for context switches
- Incremented counter before each process execution
- Printed total context switches at the end


**Challenges**: Figuring out correct placement for increment


**Solution**: Placed it before thread.start()

**Time spent**: 45 minutes

---

### Entry 5 - [March 30, 2026, 3:00 AM]
**What I did**: Implemented Feature 3 (Waiting Time)

**Details**: - Added time tracking variables
- Calculated waiting time using system time
- Displayed summary table at the end


**Challenges**: 
Understanding how to track waiting time correctly
**Solution**: 
Used lastQueueEnterTime and startTime difference
**Time spent**:  1 hours

---

### Entry 6 - [March 30, 2026,  5:00 AM]
**What I did**:  Final testing and debugging

**Details**: - Fixed issues with priority display
- Verified all features working correctly
- Reviewed output and ensured correctness


**Challenges**: Minor bugs in output formatting

**Solution**: Adjusted print statements

**Time spent**:45 minutes 

---

## Summary

**Total time spent on assignment**: [3 days ]

**Most challenging part**: 
Implementing waiting time correctly
**Most interesting learning**: 
Understanding how Round-Robin scheduling works with threads

**What I would do differently next time**:
Start earlier and test each feature step-by-step
