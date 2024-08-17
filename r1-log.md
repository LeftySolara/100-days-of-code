# #100DaysOfCode Log - Round 1 - Julianne Adams

The log of my #100DaysOfCode challenge. Started on August 4, Sunday, 2024.

## Goal

My goal for this challenge is to learn to program in Go.

## Log

### R1D1

Started working on my first Go project: a basic calculator with a GUI.
Learned some things about Go syntax and started learning how to use the
[GioUI](https://gioui.org/doc/learn/get-started) library. So far I've been able
to create a window, display a button, and align the button in the window.

[Link to today's code](https://github.com/LeftySolara/go-calculator/tree/35c9b0b589644ea69bce4a567a028f1bc2a39d47)

### R1D2

Worked on simplifying the code for the calculator project.
The existing code was too complex and confusing for someone
unfamiliar with Golang (me), so I made it a bit more tidy.

[Link to today's code](https://github.com/LeftySolara/go-calculator/tree/a0fb5d4c9ae47077399cd9845bba93e2b369a3c0)

### R1D3

Learned about variadic functions and figured out how to display multiple
buttons without having to declare and draw each individual one separately.

[Link to today's code](https://github.com/LeftySolara/go-calculator/tree/4a1acbe51f4396483cfbe358706d4f78e614b322)

### R1D4

Learned about pointers in Go. Also figured out how to make buttons clickable
in the calculator project.

[Link to today's code](https://github.com/LeftySolara/go-calculator/tree/6bbf3d7a766d6062880cb83eaa24c31f82ec3a7a)

### R1D5

Learned about structs in Go.

For the calculator project, I've migrated from GioUI to Wails. I was having a lot
of trouble with Gio, but I feel like Wails will be easier since I'm already familiar
with React and TypeScript.

[Link to today's code](https://github.com/LeftySolara/calculator/tree/67f080549e5be93234704cc16492c5d6310c16dd)

### R1D6

Added number input buttons and a display for showing the user's input.

[Link to today's code](https://github.com/LeftySolara/calculator/tree/79354573ca150c5bd8eb5e0313120d79a0d39965)

### R1D7

Started learning about interfaces in Golang. For the calculator project,
I added operator buttons and implemented a stack data structure to use for
Reverse Polish Notation.

[Link to today's code](https://github.com/LeftySolara/calculator/tree/0cb4ec4bc3742a466ba7edfa7904bdd96deba5db)

### R1D8

Learned more about Golang interfaces.

For the calculator project, I implemented a stack data structure and an evaluator function. The function goes through the stack and evaluates expressions in Reverse Polish Notation.

[Link to today's code](https://github.com/LeftySolara/calculator/tree/9e096b0a05a4952c78c0ab5706b30351062e7053)

### R1D9

Started a new project. It's just a simple task management application written in Go, using the Bubble Tea library for the TUI.

I went through some tutorials for Bubble Tea and wrote the initial program loop for my project.

[Link to today's code](https://github.com/LeftySolara/go-tasks/tree/238483e5b00c95cce221892b236dd4fc44bb326c)

### R1D10

Started learning about concurrency in Go.

For the task manager project, I added functionality for displaying tasks along
with their completion status.

[Link to today's code](https://github.com/LeftySolara/go-tasks/tree/acc97aa007bb151435152be388e7ebce90bc10f7)

### R1D11

Feeling pretty awful today, but still coding.

Started learning about buffered channels in Go.

For the task manager project, I cleaned up the task model and added the ability to navigate between tasks.
Also added a little bit of styling.

[Link to today's code](https://github.com/LeftySolara/go-tasks/tree/6d740bf98ca27eb58afa8606aaa1180b094d82d8)

### R1D12

Got stuck trying to get multiple views working.

[Link to today's code](https://github.com/LeftySolara/go-tasks/tree/498fad3f4aea888021ceee1f95d7ba819fcb9354)
