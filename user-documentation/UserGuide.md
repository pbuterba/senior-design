# Hackademia User Guide

## Introduction

Hackademia is an interactive learning platform designed for students studying topics such as programming, computer architecture, and network security. The platform provides various tools to help users understand complex concepts through hands-on experience. 

### Key Modules:
- **C-to-Assembly Emulator** (Our focus) – Converts C code into equivalent assembly, animating the call stack and registers for better visualization.
- **Buffer Overflow Module** – Demonstrates vulnerabilities in memory management and teaches secure coding practices.
- **Command Injection Module** – Explores command injection attacks and how to prevent them.

This guide focuses on the **The Dynamic Call Stack**, explaining how to use it effectively.

---

## Getting Started

### Accessing Hackademia
1. Open the Hackademia website in your browser.
2. On the landing page, click the **"Enter"** button to proceed.
3. A list of available learning modules will appear.
4. Click on **"The Dynamic Call Stack"** to enter the module.

---

## Using the C-to-Assembly Emulator

### Layout Overview
When you open the C-to-Assembly Emulator module, the page is divided into the following sections:

1. **C Code Input Box**  
   - Enter your C code here. Make sure your code is syntactically correct.

2. **Generate Assembly Code Button**  
   - After entering your code, click this button to generate the equivalent assembly code.  
   - If there’s an error in your code, an error message will be displayed.

3. **Assembly Instruction Box**  
   - Displays the generated assembly code, step-by-step.

4. **Stack Visualization**  
   - Shows the changes in the stack as you navigate through the assembly code.

5. **Registers Visualization**  
   - Displays how registers are updated at each step.

6. **Navigation Buttons**  
   - **Back**: Move to the previous step.  
   - **Next**: Move to the next step in the assembly execution.  
   - **Reset**: Clears the current input and output to start over.  
   - **Skip to End**: Displays the final state of the stack and registers.
