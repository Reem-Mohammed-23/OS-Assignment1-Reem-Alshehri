# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer: A process is an independent program with its own memory space, while a thread is a smaller unit of execution within a process that shares memory with other threads. Processes are heavier and require more resources to create and manage, whereas threads are lightweight and faster. Threads share the same memory, which allows efficient communication. In this assignment, threads were used instead of processes because they are more efficient and suitable for simulating CPU scheduling. Using processes would require more system resources and complexity.**

[Write your answer here. Consider: What is a process? What is a thread? How do they differ in terms of memory, resources, creation overhead? Why are threads more suitable for this simulation?]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer: When a process does not finish within its time quantum, it is moved to the end of the ready queue. This allows other processes to get CPU time before it runs again. The process will continue execution in the next cycle.
**

[Write your answer here. Describe the specific behavior - where does the process go? When does it run again? Give an example from your actual program output showing a process that was re-queued.]

Example from my output:
P1 completed quantum 5000ms │ Remaining time: 5842ms
P1 yields CPU for context switch
P1 added to ready queue```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example: This shows that P1 did not finish execution in its allocated time quantum, so it was paused and moved to the end of the queue. It will wait for its turn again in the next cycle.
**
[Explain what's happening in the output snippet you pasted]

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer: **

[Write your answer here. For each state, explain when P1 enters that state during the simulation. Use your understanding of the code to trace through the lifecycle.]

1. **New**: When the thread is created but not started yet.

2. **Runnable**: When the thread is added to the ready queue and waiting for CPU.

3. **Running**: When the thread is executing inside the run() method.

4. **Waiting**: When the thread is sleeping during Thread.sleep().

5. **Terminated**: When the process finishes execution and remaining time becomes zero.

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: Operating System Task Scheduling

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**:
Operating systems use scheduling algorithms to manage multiple processes.
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

### Example 2:  Web Servers

**Description**:
Web servers handle multiple user requests at the same time.
[Describe the real-world scenario or application]

**Why Round-Robin works well here**:
 It allows each request to be processed fairly and improves responsiveness.
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

---

## Summary

**Key concepts I understood through these questions:**
1. Difference between threads and processes
2. Round-Robin scheduling behavior
3. Thread lifecycle states

**Concepts I need to study more:**
1. Advanced synchronization
2. Deadlocks and concurrency control
