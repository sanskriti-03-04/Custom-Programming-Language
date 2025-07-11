# 🌀 MyLang — A Toy Programming Language from Scratch

**MyLang** is a custom-built programming language developed using Python. It includes a tokenizer, parser, compiler to bytecode, and a stack-based virtual machine (VM) capable of executing custom programs written in MyLang syntax.

This project demonstrates your mastery over language design, compiler theory, bytecode execution, systems thinking, and debugging architecture. It includes benchmarking, error handling, and AST/bytecode visualization — all in a single interpretable stack.

---

## 🚀 Project Objectives

- Build a minimal, readable, functioning language from scratch
- Understand compiler internals, return statements, stack frames
- Support bytecode compilation and stack-based VM execution
- Benchmark and visualize code execution
- Align the project with interview and internship screening expectations at companies like Google, Amazon, Atlassian, and Microsoft

---

## 🔧 Key Features

| Feature | Description |
|--------|-------------|
| 🧠 Lexer | Tokenizes MyLang source into tokens |
| 🌲 Parser | Builds an Abstract Syntax Tree (AST) |
| ⚙️ Compiler | Compiles AST into bytecode |
| 🔁 Virtual Machine | Executes bytecode with a stack |
| 🔁 Functions & Return | Supports `def`, `return`, function calls |
| 💥 Error Handling | Detects undefined variables, division by zero, bad returns |
| 📊 Benchmarking | Instructions executed, time taken, IPS |
| 📈 AST & Bytecode Graphs | Visual graph of execution tree and instruction flow |

---

##🧯 Error Handling
 
| Error Type	              | Trigger	                    | Example
| NameError	                | Undefined variable	        | print(x)
| ZeroDivisionError	        | Divide by zero	            | 10 / 0
| TypeError         	      | Wrong number of arguments	  | foo() when foo(x)
| RuntimeError	            | Stack/return issue	        | RET without value

Errors are descriptive and caught during VM execution.

---

##⏱️ Benchmark:
Instructions executed: 13
Time taken: 0.000021 seconds
Instructions per second: 619047.62 IPS
Useful for performance comparison, interpreter optimization, and complexity measurement.

---

## 📊 Visualization
MyLang uses graphviz to generate:

✅ Abstract Syntax Trees (AST)

✅ Bytecode instruction flow

These are rendered as PNGs in the Colab notebook or exported for GitHub.


---


## 🧪 Standard Examples Included
square.lang

arithmetic.lang

nested_calls.lang

double_call.lang


---

## 🛠️ Installation & Usage
▶️ [In Google Colab]{https://colab.research.google.com/drive/1sJ01X3zacW_r6SHXyw8UstznHrCC4hrf?usp=sharing} 
Upload your files to Colab

Run the notebook demo.ipynb

Use run_example() to execute code


---


## 📌 Future Roadmap
 Add if / else conditionals

 Add while and for loops

 Add function scope and closures

 Add file imports or standard library

 Add memory profiling and garbage collection


 ---

 
