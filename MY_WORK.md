# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Mastourah Nayil Althobaiti |
| **Student ID** | 447540232 |
| **University Email** | 447540232@std.psau.edu.sa |
| **GitHub Username** | mstora124 |
| **Repository Link** | https://github.com/mstora124/OS-Assignment1-Mastourah-Althobaiti.git |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 6, 2026, 3:00 PM]
**What I did**:Forked the repository and reviewed the project structure.

**Details**:Forked the starter code repository and renamed it to `OS-Assignment1-Mastourah-Althobaiti`.
- Read through `SchedulerSimulation.java` and analyzed the classes and threads.
- Set up the project environment and tested running the baseline code.

**Challenges**:Understanding how threads manage individual processes in the round-robin loop.

**Solution**:Traced the code execution flow step-by-step using online compiler tools.

**Time spent**:45 minutes

---

### Entry 2 - [October 7, 2026, 4:15 PM]
**What I did**:Implemented Feature 1: Process Priority.

**Details**:- Added a `priority` field (1-10) to the `Process` class constructor.
- Updated the process generation loop to assign a random priority to each process.
- Modified the ready queue insertion message to display the priority value clearly.

**Challenges**:Ensuring the priority value displays correctly without breaking existing ANSI color codes.

**Solution**:Appended the priority string carefully using the defined color variables.

**Time spent**:1 hour

---

### Entry 3 - [October 8, 2026, 5:30 PM]
**What I did**:Implemented Feature 2: Context Switch Counter.

**Details**:- Declared a `contextSwitchCounter` variable inside the `main` method.
- Incremented the counter every time a thread is dequeued and started in the scheduling loop.
- Printed the total number of context switches at the end of the simulation.

**Challenges**:Making sure the counter only increments on actual process switches and not re-enqueues.

**Solution**:Placed the increment statement right before `currentThread.start()` in the main scheduler loop.

**Time spent**:45 minutes

---

### Entry 4 - [October 9, 2026, 6:00 PM]
**What I did**:Implemented Feature 3: Waiting Time Tracking and Summary Table.

**Details**:- Added arrival, waiting, and completion time tracking fields to the `Process` class using system timestamps.
- Calculated turnaround time and waiting time accurately for each process.
- Created and formatted a final summary table displaying process names, burst times, waiting times, and turnaround times.

**Challenges**:Handling waiting time updates correctly when processes are paused and re-enqueued multiple times.

**Solution**:Tracked `lastStartTime` and accumulated waiting intervals dynamically across quantum cycles.

**Time spent**:1.5 hours

---

### Entry 5 - [October 10, 2026, 8:00 PM]
**What I did**:Finalized documentation, recorded demo video, and verified commits.

**Details**:- Completed all sections in `MY_WORK.md` including reflections and technical answers.
- Recorded the 2-3 minute demonstration video showing code execution and features.
- Pushed all final commits and documentation to the public GitHub repository.

**Challenges**:Ensuring the demo video length stayed within the 2-3 minute requirement.

**Solution**:Prepared a brief script covering name, ID, code overview, and running output beforehand.

**Time spent**:1 hour

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [ 5 hours]

**Most challenging part**:Tracking cumulative waiting times accurately across multiple round-robin context switches.

**Most interesting learning**:Seeing how Java multithreading and system timestamps can simulate low-level OS scheduling behaviors.

**What I would do differently next time**:Start modularizing the code into separate files earlier in the development process.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*


Working on this CPU scheduling simulation helped me deeply understand how operating systems manage competing processes using a fixed time quantum. Implementing the Round-Robin algorithm visually clarified why processes are frequently interrupted and returned to the ready queue. I gained strong practical experience in Java multithreading, synchronization, and handling threads safely using `Thread.start()` and `Thread.join()`. Observing how `Thread.sleep()` simulates CPU burst execution made theoretical OS concepts much more tangible. This assignment bridged the gap between textbook operating system principles and actual executable code implementation.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part of this assignment was implementing accurate waiting time tracking for Feature 3 across multiple context switches. Since processes are repeatedly interrupted and re-enqueued into the ready queue, calculating their exact waiting duration required precise timestamp management. I had to carefully track when a process arrived, when it started its quantum, and how long it spent waiting in the queue between cycles. Debugging these time calculations took multiple iterations to ensure the final summary table displayed correct values. Overcoming this required a thorough re-reading of the process execution lifecycle and careful state variable updates.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I overcame my development challenges by breaking down complex problems into smaller, testable steps and utilizing incremental debugging. Whenever a compilation error or incorrect calculation occurred, I used targeted `System.out.println` statements to inspect variable states and thread behaviors in real-time. Reviewing the project instructions and comparing my implementation against the requirements in the README helped clarify expected outcomes. When dealing with Git and GitHub version control, I tested small commits and verified changes in the web interface to ensure everything synced properly. Testing the code frequently after each modification ensured that new features integrated smoothly without breaking existing functionality.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading concepts are essential in modern software development for building responsive, high-performance applications across various domains. For instance, in a web browser, separate threads handle network requests, rendering web pages, and processing user inputs concurrently so the interface never freezes. In mobile applications, background threads perform heavy tasks like database queries or file downloads, leaving the main UI thread free to handle smooth animations. Similarly, game engines use multiple threads to manage physics calculations, audio rendering, and artificial intelligence simultaneously. Understanding CPU scheduling and thread management provides a foundational basis for optimizing resource allocation in these complex real-world systems.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

Thread vs Process
A process is an independent execution unit with its own isolated memory space and system resources managed by the operating system, whereas a thread is a lightweight execution unit existing within a process that shares the same memory space. In our Java simulation, each simulated process implements `Runnable` and executes inside its own dedicated `Thread` object, sharing common structures like the ready queue and process map. We used threads in this assignment because creating lightweight threads introduces much less overhead and allows faster communication and context switching compared to spawning separate operating system processes. This is reflected in our code where threads are instantiated via `new Thread(process)` inside the `addProcessToQueue` method.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

Ready Queue Behavior
In Round-Robin scheduling, when a process does not finish executing within its allotted time quantum, it is preempted and placed back at the back of the ready queue to ensure fair CPU sharing. In my program execution, processes with large burst times were re-enqueued multiple times depending on how many quanta they required to complete. For example, a process like P1 with a burst time significantly larger than the time quantum was dequeued, executed for one quantum, and then re-added to the ready queue multiple times before its remaining time reached zero. This re-enqueuing mechanism is crucial for fairness because it prevents any single long-running process from monopolizing the CPU, allowing all other processes regular opportunities to make progress.

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 enters the New state when a new `Thread` object is instantiated in the `addProcessToQueue` method (`Thread thread = new Thread(process);`) before execution begins.

2. **Runnable**: P1 becomes Runnable when the scheduler calls `currentThread.start()`, signaling the Java Virtual Machine that the thread is ready to run.

3. **Running**: P1 enters the Running state when the CPU allocates execution time to its `run()` method, where it simulates work using `Thread.sleep()`.

4. **Waiting**: P1's thread may enter a waiting or timed-waiting state during `Thread.sleep()`, while the main scheduler thread enters a waiting state when it calls `currentThread.join()` to wait for the quantum to finish.

5. **Terminated**: P1 enters the Terminated state once its `remainingTime` reaches zero and its `run()` method completes execution entirely.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario] Operating System CPU Scheduling

**Description**:
Modern operating systems like Linux and Windows use CPU scheduling algorithms to allocate processor time among dozens of active background services and user applications.

**Why Round-Robin works well here**:
Round-Robin scheduling works exceptionally well because it guarantees fairness and prevents starvation, ensuring that every running application gets predictable, responsive access to the CPU time slices.

### Example 2: [Name of application/scenario] Web Server Request Handling

**Description**:
High-traffic web servers manage thousands of concurrent client requests simultaneously by assigning incoming connections to separate worker threads.

**Why Round-Robin works well here**:
Using fair scheduling ensures that no single large file download or heavy database query can starve other incoming quick requests, maximizing overall system responsiveness and predictable throughput.

## Summary

**Key concepts I understood through these questions:**
1.How Java threads manage concurrent process execution using the Runnable interface and thread synchronization methods.
2.The operational mechanism of Round-Robin scheduling and why re-enqueuing unfinished processes ensures CPU fairness.
3.The distinct states of a thread lifecycle from creation to termination and how system timestamps calculate waiting metrics.

**Concepts I need to study more:**
1.Advanced synchronization locks and thread inter-communication mechanisms.
2.Multi-core processor scheduling optimization and overhead handling.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
