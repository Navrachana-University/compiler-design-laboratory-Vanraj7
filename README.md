# 🌊 Outer Banks Compiler: A Coastal-Inspired Programming Tool

## 📜 Project Description
The *Outer Banks Compiler* is a themed programming language and compiler project inspired by the charm and raw energy of the Outer Banks. Built using powerful tools like *Flex* and *Bison*, it brings a structured yet aesthetically engaging approach to programming language design.

Through simplified syntax and coastal metaphors, it makes learning compiler concepts intuitive and engaging — perfect for academic exploration and creative expression.

---

## 🧭 Design Philosophy
- 🌅 *Clarity of Horizon* — Maintain simple, readable syntax  
- 🧭 *Purpose of Voyage* — Each rule and token has a distinct function  
- 🌊 *Flow of Tides* — Modular phases that smoothly convert source to intermediate code  
- 🐚 *Elegance and Naturalness* — Themes and identifiers inspired by coastal culture  

---

## 👤 Student Information
*Student Name:* Vanraj Jhala  
*Enrollment ID:* 22000419

---

## 📦 Project Components
| File Name       | Type       | Description                                       |
|------------------|------------|---------------------------------------------------|
| obx.y          | Y File     | Bison grammar file (defines parsing rules)        |
| obx.l          | L File     | Flex lexer file (defines tokens and regex rules)  |
| obx.tab.c      | C File     | Bison-generated parser logic                      |
| obx.tab.h      | H File     | Token definitions from Bison                      |
| lex.yy.c       | C File     | Flex-generated lexer code                         |
| obxc / obxc.exe | Executable | Final compiler binary                          |
| sample1.obx    | OBX File   | Sample program in Outer Banks language            |
| output.tac     | TAC File   | Generated three-address intermediate code         |

---

## ⚙️ How to Compile and Run Outer Banks Programs

### 🔧 Compilation Steps (on Unix/Linux)
1. *Generate the parser with Bison:*
   bash
   bison -d obx.y
2. **Compile everything with GCC:**
   bash
   gcc lex.yy.c obx.tab.c -o obxc
3. *Execute a sample OBX program:*
   ```bash
   ./obxc sample1.obx

Check the output:
Intermediate code is saved in output.tac.
📄 Example Program (sample1.obx)
obx

Copy
pogues hideout
    jj x;
    treasure x = 42;
    trade(x);
hideout
💻 System Requirements
GCC Compiler
Flex (Fast Lexical Analyzer)
Bison (GNU Parser Generator)
Unix/Linux shell (preferred)
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
