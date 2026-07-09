# SIT315 – Programming Paradigms

> Deakin University · 4th Semester · C++ · Vansh Khanna

Assignments from SIT315 covering core programming paradigms including **Object-Oriented Programming (OOP)**, **generic programming** (templates), **concurrent/parallel programming** (OpenMP, MPI, pthreads), and **functional-style patterns** in C++.

---

## Key Paradigms Covered

| Paradigm | Topics |
|---|---|
| Object-Oriented | Classes, inheritance, polymorphism |
| Generic Programming | Templates, STL containers & algorithms |
| Concurrent / Parallel | pthreads, OpenMP, MPI |
| Functional Patterns | Lambdas, higher-order functions in C++ |

---

## Assignment Index

| Folder | Description |
|---|---|
| [M1.S1P](./M1.S1P) | Module 1 – Sequential task (Pass) |
| [M1.S2P](./M1.S2P) | Module 1 – Sequential task 2 (Pass) |
| [M1.T1P](./M1.T1P) | Module 1 – Threading intro (Pass) |
| [M2.S1P](./M2.S1P) | Module 2 – Parallel task (Pass) |
| [M2.S2P](./M2.S2P) | Module 2 – Parallel task 2 (Pass) |
| [M2.S3P](./M2.S3P) | Module 2 – Parallel task 3 (Pass) |
| [M2.T1P](./M2.T1P) | Module 2 – Threading task (Pass) |

---

## How to Build & Run

```bash
# Clone the repo
git clone https://github.com/VK7160/SIT315.git
cd SIT315/<folder>

# Compile a standard C++ file
g++ -std=c++17 -o main main.cpp && ./main

# Compile with OpenMP (parallel tasks)
g++ -std=c++17 -fopenmp -o main main.cpp && ./main

# Compile with MPI
mpic++ -o main main.cpp && mpirun -np 4 ./main
```

---

*Vansh Khanna — VK7160*
