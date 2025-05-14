# 🌊 Outer Banks Compiler

**A Coastal-Inspired Programming Tool Built with Flex & Bison**

---

## 📜 Overview

**Outer Banks Compiler** is a themed compiler and programming language inspired by the serene yet powerful essence of the **Outer Banks**. Developed using **Flex** and **Bison**, this project combines the rigor of compiler design with the elegance of coastal metaphors — making it perfect for academic exploration and creative expression.

Whether you're diving into lexical analysis or exploring syntax trees, this project turns compiler construction into a voyage.

---

## 🧭 Design Philosophy

- 🌅 **Clarity of Horizon** — Intuitive, readable syntax for learners and explorers alike  
- 🧭 **Purpose of Voyage** — Each token and rule plays a meaningful role  
- 🌊 **Flow of Tides** — Modular and smooth compilation pipeline (Lex → Parse → 3AC)  
- 🐚 **Elegance and Naturalness** — Naming and syntax inspired by beach life and coastal culture  

---

## 👤 Student Info

- **Name:** Vanraj Jhala  
- **Enrollment ID:** 22000419

---

## 📁 Project Structure

| File Name        | Type        | Description                                       |
|------------------|-------------|---------------------------------------------------|
| `obx.y`          | Bison File  | Grammar rules for parsing                         |
| `obx.l`          | Flex File   | Lexical rules and token definitions               |
| `obx.tab.c`      | C File      | Bison-generated parser implementation             |
| `obx.tab.h`      | Header File | Token definitions from Bison                      |
| `lex.yy.c`       | C File      | Flex-generated lexer code                         |
| `obxc` / `obxc.exe` | Executable | Final compiled compiler binary                    |
| `sample1.obx`    | OBX Source  | Sample Outer Banks language program               |
| `output.tac`     | TAC File    | Generated Three-Address Code (3AC)                |

---

## ⚙️ How to Build and Run

### 🛠 Prerequisites

- GCC (GNU Compiler Collection)  
- Flex (Fast Lexical Analyzer)  
- Bison (GNU Parser Generator)  
- Unix/Linux shell (preferred environment)

### 🚀 Build Steps

```bash
# Step 1: Generate parser files using Bison
bison -d obx.y

# Step 2: Generate lexer using Flex
flex obx.l

# Step 3: Compile all with GCC
gcc lex.yy.c obx.tab.c -o obxc

# Step 4: Run a sample OBX program
./obxc sample1.obx

—

### 📄 Sample OBX Program (sample1.obx)
pogues hideout
    jj x;
    treasure x = 42;
    trade(x);
hideout

—

### 🚤 Key Features
— Custom programming language with Outer Banks-inspired syntax
— Tokenization via Flex
— Syntax parsing via Bison
— Three-Address Code (3AC) Generation
— Modular and clean file structure
— Ideal for compiler design learning and academic use

—

Acknowledgments
— Prof. Vaibhavi Patel – For continuous guidance and mentorship
— Nishil Patel – For active collaboration and testing

—

📚 Inspiration
— Just like the Outer Banks — sometimes unpredictable, often calm, always wild — this compiler project finds balance in simplicity, expressiveness, and technical depth. It turns a complex subject like compiler construction into an inspiring journey of creativity and logic.
