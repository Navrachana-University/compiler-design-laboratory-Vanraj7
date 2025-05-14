# 🌊 Outer Banks Compiler: A Coastal-Inspired Programming Tool

## 📜 Project Description
The **Outer Banks Compiler** is a themed programming language and compiler project inspired by the charm and raw energy of the Outer Banks. Built using powerful tools like **Flex** and **Bison**, it brings a structured yet aesthetically engaging approach to programming language design.

Through simplified syntax and coastal metaphors, it makes learning compiler concepts intuitive and engaging — perfect for academic exploration and creative expression.

---

## 🧭 Design Philosophy
- 🌅 **Clarity of Horizon** — Maintain simple, readable syntax  
- 🧭 **Purpose of Voyage** — Each rule and token has a distinct function  
- 🌊 **Flow of Tides** — Modular phases that smoothly convert source to intermediate code  
- 🐚 **Elegance and Naturalness** — Themes and identifiers inspired by coastal culture  

---

## 👤 Student Information
**Student Name:** Vanraj Jhala  
**Enrollment ID:** 22000419

---

## 📦 Project Components
| File Name       | Type       | Description                                       |
|------------------|------------|---------------------------------------------------|
| `obx.y`          | Y File     | Bison grammar file (defines parsing rules)        |
| `obx.l`          | L File     | Flex lexer file (defines tokens and regex rules)  |
| `obx.tab.c`      | C File     | Bison-generated parser logic                      |
| `obx.tab.h`      | H File     | Token definitions from Bison                      |
| `lex.yy.c`       | C File     | Flex-generated lexer code                         |
| `obxc` / `obxc.exe` | Executable | Final compiler binary                          |
| `sample1.obx`    | OBX File   | Sample program in Outer Banks language            |
| `output.tac`     | TAC File   | Generated three-address intermediate code         |

---

## ⚙️ How to Compile and Run Outer Banks Programs

### 🔧 Compilation Steps (on Unix/Linux)
1. **Generate the parser with Bison:**
   ```bash
   bison -d obx.y
