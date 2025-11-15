# Homework 10.11.2025
## Compiling a Multi-File C++ Program

This project demonstrates how to build a simple C++ program from multiple source files.  
The program prints:
__hello__

## 📁 Project Files
- __main.cpp__ — entry point  
- __file.cpp__ — function implementation  
- __file.h__ — function declaration  

## 🔧 Compilation

### 1) Create object files:
g++ -c main.cpp
g++ -c file.cpp
### 2) Linking:
g++ main.o file.o -o program.out

### 3) Run:
./program.out

markdown
Копіювати код

## ✔️ Explanation
- The `-c` flag means "compile only" — it generates `.o` object files.
- After linking, you get the executable `program.out`.
![ням](https://github.com/Smyrfy/picture/blob/main/f07650716922a8f7059cea3a51374041.jpg?raw=true)



