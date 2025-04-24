# 🧑‍💼 Employee Management System (C Language)

This project is a **Command-Line Based Employee Management System** developed in **C language**. It simulates the internal HR operations of a company and allows one employee to:

- Register with personal details like name, Aadhaar number, email, and mobile number.
- Secure access with an employee code and a clue-based verification.
- Automatically assign a job role based on their years of experience.
- View their salary based on the assigned role.
- Apply for leaves, with real-time calculation of remaining leave balance.
- Update their information anytime securely.

The project uses a simple `struct` to store employee data in memory, simulates authentication, and includes core programming concepts like:
- Functions
- Structures
- Loops & conditionals
- Basic authentication logic
- Random code generation

---

## ✨ Features

- 🔐 Employee authentication using code & hint
- 📝 Add and view employee details
- 🏷️ Assign job post based on experience
- 💰 View salary based on role
- 📩 Apply for leave with auto-calculation of remaining leaves
- 🔄 Update employee info (name, adhar, email, mobile)

---

## 🛠️ Built With

- C Language
- Standard C Libraries (`stdio.h`, `stdlib.h`, `string.h`, `time.h`)

---

## 🚀 How to Run

1. Compile the code using GCC:
   ```bash
   gcc employee_management.c -o employee_management
