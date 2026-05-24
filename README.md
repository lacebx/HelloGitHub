# HelloGitHub, C++ Console Fundamentals

This is where the C++ grind started. `HelloGitHub` is a small console application built in Visual Studio, one of my early projects learning how to separate code into headers, source files, and clean `main()` entry points.

It's nothing flashy. It prints "Hello GitHub!" and counts numbers. But what matters here is the structure: a `.h` header declaring functions, a `Functions.cpp` implementing them, and a clean `main` calling them. That's real software organization.

Honestly birarenze how the simplest programs teach the most important habits.

## What It Does
* Displays "Hello GitHub!" to the console
* Counts from 1 to `n` using a loop function (`showNums`)
* Demonstrates function declaration/definition separation
* Structured as a proper Visual Studio C++ solution

## Project Structure
```
HelloGitHub/
├── ConsoleApplication14/
│   ├── helloGithub.cpp         # Entry point (main)
│   ├── helloGithub.h           # Function declarations
│   └── helloGithubFunctions.cpp # Function definitions
└── ConsoleApplication14.sln    # Visual Studio solution file
```

## Tech Stack
* **Language:** C++
* **IDE:** Visual Studio
* **Build:** MSVC (Visual Studio compiler)

## Running It
Open `ConsoleApplication14.sln` in Visual Studio and hit **Run (F5)**.

Or compile manually:
```
g++ helloGithub.cpp helloGithubFunctions.cpp -o hello
./hello
```

## Why This Exists
Every developer has one of these. The first time you figure out how to split your code across multiple files, declare something in a header, and have it all link together correctly, that's a small win that hits different. This is mine.
