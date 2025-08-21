# 🚀 42 School C Piscine Exam Solutions & Practice Guide

[![42 School](https://img.shields.io/badge/42-School-000000?style=flat&logo=42&logoColor=white)](https://42.fr/)
[![C Programming](https://img.shields.io/badge/C-Programming-blue?style=flat&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ayoub0x1/C-Piscine-exam?style=social)](https://github.com/ayoub0x1/C-Piscine-exam/stargazers)

> **Complete collection of 42 School C Piscine exam exercises with solutions, practice tests, and study guide for levels 0-5**

## 📋 Table of Contents

- [🎯 About](#-about)
- [📁 Repository Structure](#-repository-structure)
- [🏆 Exam Levels Overview](#-exam-levels-overview)
- [🚀 Quick Start](#-quick-start)
- [📚 Study Guide](#-study-guide)
- [💡 Tips for Success](#-tips-for-success)
- [🔥 All Solutions](#-all-solutions)
- [📊 Progress Tracking](#-progress-tracking)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

## 🎯 About

This repository contains **comprehensive solutions and practice materials** for the **42 School C Piscine exams**. Perfect for students preparing for their Friday exams at 42 Network schools worldwide including **1337 School**, **42 Paris**, **42 Silicon Valley**, and all other 42 campuses.

### 🔍 What You'll Find:
- ✅ **77+ Complete C Solutions** for all exam levels (0-5)
- 📖 **Detailed Subject Files** for every exercise
- 🏗️ **Organized Structure** matching real exam environment
- 🎯 **Practice Examples** with expected outputs
- 📈 **Progressive Difficulty** from beginner to advanced
- 🚀 **Optimized Code** following 42 Norm standards

### 🎓 Perfect For:
- 42 School students preparing for C Piscine exams
- Programming beginners learning C fundamentals
- Students practicing algorithmic thinking
- Anyone preparing for coding interviews

## 📁 Repository Structure

```
📦 42-C-Piscine-Exam-Solutions/
├── 📂 All_Solutions/           # 🔥 Centralized solutions directory
│   ├── 📂 Level 00/           # Basic output, loops, conditions
│   ├── 📂 Level 01/           # Strings, basic algorithms
│   ├── 📂 Level 02/           # Intermediate string manipulation
│   ├── 📂 Level 03/           # Advanced algorithms, memory
│   ├── 📂 Level 04/           # Complex data structures
│   └── 📂 Level 05/           # Expert level challenges
├── 📂 Level 00/               # Original exercise folders with subjects
├── 📂 Level 01/               # Each contains subject.en.txt files
├── 📂 Level 02/               # And example files where applicable
├── 📂 Level 03/
├── 📂 Level 04/
├── 📂 Level 05/
└── 📄 README.md               # This comprehensive guide
```

## 🏆 Exam Levels Overview

### 📝 Level 0 (Beginner)
**Topics:** Basic I/O, Simple Loops, Character Operations
- `hello` - Hello World program
- `aff_a` - Display single character
- `ft_countdown` - Number countdown
- `maff_alpha` - Alphabet operations

### 📝 Level 1 (Basic)
**Topics:** String Basics, Simple Functions, ASCII Manipulation
- `ft_strlen` - String length calculation
- `repeat_alpha` - Character repetition
- `rot_13` - Caesar cipher ROT13
- `fizzbuzz` - Classic programming challenge

### 📝 Level 2 (Intermediate)
**Topics:** String Manipulation, Bit Operations, Mathematics
- `inter` - String intersection
- `union` - String union operations
- `ft_atoi` - String to integer conversion
- `print_bits` - Binary representation

### 📝 Level 3 (Advanced)
**Topics:** Memory Management, Complex Algorithms, Mathematical Functions
- `ft_range` - Dynamic array creation
- `hidenp` - String hiding algorithm
- `add_prime_sum` - Prime number calculations
- `ft_list_size` - Linked list operations

### 📝 Level 4 (Expert)
**Topics:** Complex Data Structures, Advanced Algorithms
- `ft_itoa` - Integer to string conversion
- `sort_list` - Linked list sorting
- `flood_fill` - Graph traversal algorithm
- `ft_split` - String splitting function

### 📝 Level 5 (Master)
**Topics:** Memory Debugging, Complex String Processing, Advanced Parsing
- `brackets` - Bracket matching algorithm
- `rpn_calc` - Reverse Polish Notation calculator
- `cycle_detector` - Linked list cycle detection

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/ayoub0x1/42-C-Piscine-Exam-Solutions.git
cd 42-C-Piscine-Exam-Solutions
```

### 2. Navigate to Any Exercise
```bash
# View original exercise with subject
cd "Level 01/1-0-ft_strlen"
cat subject.en.txt

# Access the solution
cd "../../All_Solutions/Level 01/1-0-ft_strlen"
```

### 3. Compile and Test
```bash
gcc -Wall -Wextra -Werror ft_strlen.c -o ft_strlen
./ft_strlen
```

## 📚 Study Guide

### 🔥 Essential C Concepts for 42 Exams:

1. **Memory Management**
   - `malloc()`, `free()`
   - Pointer arithmetic
   - Memory leaks prevention

2. **String Manipulation**
   - String functions (`strlen`, `strcpy`, `strcmp`)
   - Character arrays vs strings
   - Null termination

3. **Data Structures**
   - Arrays and multi-dimensional arrays
   - Linked lists (creation, traversal, deletion)
   - Stacks and queues concepts

4. **Algorithms**
   - Sorting algorithms (bubble, selection)
   - Search algorithms (linear, binary)
   - Recursion vs iteration

5. **42 Norm Compliance**
   - Function length limits
   - Variable naming conventions
   - Proper header inclusion

## 💡 Tips for Success

### 🎯 Exam Day Strategy:
- ✅ **Read the subject carefully** - Understand requirements completely
- ✅ **Start with easier exercises** - Build confidence first
- ✅ **Test your functions** - Always verify with different inputs
- ✅ **Check edge cases** - NULL pointers, empty strings, zero values
- ✅ **Follow 42 Norm** - Code style matters for evaluation
- ✅ **Manage your time** - Don't spend too long on one exercise

### 🚫 Common Mistakes to Avoid:
- ❌ Including main() when only function is required
- ❌ Forgetting to handle edge cases
- ❌ Memory leaks in dynamic allocation
- ❌ Not respecting function prototypes
- ❌ Submitting before thorough testing

### 🔧 Compilation Commands:
```bash
# Basic compilation
gcc -Wall -Wextra -Werror file.c

# With debugging symbols
gcc -Wall -Wextra -Werror -g file.c

# For memory checking with valgrind
gcc -Wall -Wextra -Werror -g file.c && valgrind ./a.out
```

## 🔥 All Solutions

All exercise solutions are centrally located in the `All_Solutions/` directory for easy access:

```bash
All_Solutions/
├── Level 00/ (11 exercises) - Fundamentals
├── Level 01/ (13 exercises) - Basic Programming
├── Level 02/ (14 exercises) - Intermediate Concepts
├── Level 03/ (14 exercises) - Advanced Algorithms
├── Level 04/ (13 exercises) - Complex Structures
└── Level 05/ (8 exercises) - Expert Challenges
```

**Total: 77+ Complete Solutions**

## 📊 Progress Tracking

Track your exam preparation progress:

- [ ] **Level 0 Complete** (Basic output and simple operations)
- [ ] **Level 1 Complete** (String basics and simple algorithms)
- [ ] **Level 2 Complete** (Intermediate string manipulation)
- [ ] **Level 3 Complete** (Advanced algorithms and memory)
- [ ] **Level 4 Complete** (Complex data structures)
- [ ] **Level 5 Complete** (Expert-level challenges)

## 🌟 Related Resources

- [42 Norm PDF](https://cdn.intra.42.fr/pdf/pdf/960/norme.en.pdf) - Official coding standard
- [42 Cursus](https://42.fr/en/the-program/software-engineer-degree/) - Complete curriculum overview
- [C Programming Tutorial](https://www.learn-c.org/) - Additional C learning resource

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **🍴 Fork** the repository
2. **🌿 Create** a feature branch (`git checkout -b feature/improvement`)
3. **📝 Commit** your changes (`git commit -am 'Add new solution'`)
4. **🚀 Push** to the branch (`git push origin feature/improvement`)
5. **🔄 Create** a Pull Request

### 📋 Contribution Guidelines:
- Follow 42 Norm standards
- Include proper documentation
- Test all solutions thoroughly
- Provide alternative approaches when possible

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Show Your Support

If this repository helped you with your 42 exams, please consider:
- ⭐ **Starring** this repository
- 🍴 **Forking** it for your own use
- 📢 **Sharing** it with fellow 42 students
- 🐛 **Reporting** any issues you find

---

### 📞 Connect & Support

**Made with ❤️ for the 42 Community**

[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=social&logo=github)](https://github.com/ayoub0x1)
[![42 Profile](https://img.shields.io/badge/42-Profile-blue)](https://profile.intra.42.fr/)

> *"The only way to do great work is to love what you do."* - Steve Jobs

**Good luck with your exams! 🚀**
