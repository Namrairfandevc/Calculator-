# GUI Calculator (Native Win32)

A lightweight and efficient desktop calculator built using **C++** and the **Win32 API**. This project was developed to demonstrate low-level Windows programming, handling system messages, and creating a functional graphical user interface without the use of heavy external frameworks.

---

## 👤 Developer Information

* **Developer Name:** Namra Irfan

---

## 🚀 Key Features

* **Native Performance:** Built directly with `<windows.h>` for instant execution and minimal resource usage.
* **Arithmetic Operations:** Supports Addition, Subtraction, Multiplication, and Division.
* **Safe Division:** Includes logic to handle division by zero errors.
* **Clean Interface:** Features a dual-input layout with a clear result display.
* **Native UI Elements:** Uses standard Windows buttons and edit controls for a classic desktop feel.

## 🛠️ Tech Stack

* **Language:** C++
* **Framework:** Win32 API (Native Windows Programming)
* **IDE:** Dev-C++
* **Compiler:** MinGW / GCC

## 📂 How to Run

### Method 1: Using Dev-C++ (Easiest)
1. Open the project by double-clicking the `calculator.dev` file.
2. In the Dev-C++ menu, go to **Execute** > **Compile & Run** (or simply press **F11**).

### Method 2: Command Line (MinGW)
To compile the source code manually using the terminal, run:
```bash
g++ calculator.cpp -o calculator.exe -mwindows
