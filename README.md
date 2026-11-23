# Student Management System

A simple C++ console mini-project demonstrating core Object-Oriented Programming (OOP) concepts including encapsulation, constructors, accessors/mutators, and arrays of objects.

## Concepts Implemented

- *Encapsulation*: Private data members (rollNo, name, marks) protect student records from direct external modification.
- *Parameterized Constructor*: Initializes each Student object and reuses setMarks() for centralized validation.
- *Getters & Validating Setter*:
  - getRollNo(), getName(), and getMarks() provide read-only access.
  - setMarks(float m) accepts values between 0 and 100; invalid values print a warning and default to 0.
- *Member Function*: display() prints formatted student details.
- *Object as Function Argument*: printResult(Student s) is a non-member function that evaluates pass/fail status (>= 40 to pass) using public getters.
- *Array of Objects*: Manages a batch of Student objects in main(), including a re-evaluation update.

## Prerequisites

- A C++ compiler such as g++ (MinGW-w64 on Windows, GCC/Clang on Linux/macOS).

## How to Compile and Run

1. Clone the repository or download student_management.cpp.
2. Compile the source file:

```bash
g++ student_management.cpp -o student_management
