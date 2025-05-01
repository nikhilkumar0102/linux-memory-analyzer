# 🧠 Memnoir – Linux Memory Analyser Tool

**Memnoir** is a lightweight memory analysis tool for Linux, built to inspect and debug C/C++ applications. It analyzes **heap**, **stack**, **buffers**, identifies **memory leaks**, and assists in **fuzzing** workflows — all from a simple command-line interface.

---

## 🔧 Key Features

- Inspect **heap** and **stack** memory usage
- Detect **buffer overflows** and **underflows**
- Identify potential **memory leaks**
- Assist in **fuzz testing** for C/C++ binaries
- Run directly from terminal after global setup

---

## 🚀 Installation (Global Access Setup)

To make `memnoir` globally accessible from your terminal:

```bash
# Step 1: Clone or download the repository
git clone https://github.com/your-username/linux-memory-analyser.git

# Step 2: Enter the directory
cd linux-memory-analyser

# Step 3: Make it executable
chmod +x memnoir-linux

# Step 4: Rename the file
mv memnoir-linux memnoir

# Step 5: Move it to /usr/local/bin for global use
sudo mv memnoir /usr/local/bin/

# Usage
memnoir your_file.c
```
## 📂 Use Cases
- Debugging segmentation faults, overflows, and leaks
- Learning about memory layout in C/C++ programs
- Lightweight fuzzing assistance
- Education and training for students or researchers

## 🐧 Requirements
- Linux (Ubuntu, Fedora, Kali, Arch, etc.)
- C or C++ source/binary files
- sudo access (for installation)

## 📜 License
- MIT License

## 🙋 Author
- Created with ❤️ by Nikhil Kumar
- Open to contributions, issues, and suggestions!



