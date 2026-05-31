# 💻 CS50X — Introduction to Computer Science

> My personal solutions to Harvard's [CS50's Introduction to Computer Science](https://cs50.harvard.edu/x/) — the world's largest and most beloved introductory CS course.

---

## 📌 About This Repository

This repository contains my solutions to the problem sets, labs, and the final project from **CS50X**, offered by Harvard University through [edX](https://www.edx.org/). The course spans a wide range of topics — from low-level memory management in C to full-stack web development — making it one of the most comprehensive introductory CS courses available, completely free.

These solutions are uploaded here to:
- Document my personal journey through the course
- Serve as a **learning reference** for others tackling the same problems
- Showcase different approaches to classic CS problems

---

## ⚠️ Academic Honesty Notice

> **Please read this carefully before using anything in this repository.**

CS50 enforces a strict [Academic Honesty Policy](https://cs50.harvard.edu/x/honesty/). If you are currently enrolled in CS50X or any related course, **do not copy, submit, or present these solutions as your own work.**

This repository exists **solely for educational purposes** — to help you understand an approach after a genuine attempt, compare logic, or get unstuck when truly needed. Submitting someone else's work as your own not only violates the course policy, but robs you of the learning that makes CS50 worth doing.

**Try first. Struggle a little. Then look. That's how it works.**

---

## 📂 Course Structure

| Week | Topic | Language(s) |
|------|-------|-------------|
| Week 0 | Scratch | Scratch |
| Week 1 | C | C |
| Week 2 | Arrays | C |
| Week 3 | Algorithms | C |
| Week 4 | Memory | C |
| Week 5 | Data Structures | C |
| Week 6 | Python | Python |
| Week 6.5 | Artificial Intelligence | Python |
| Week 7 | SQL | SQL |
| Week 8 | HTML, CSS, JavaScript | Web |
| Week 9 | Flask | Python + Web |
| Week 10 | Cybersecurity | — |
| Final | Final Project | Open-ended |

> Folders will be added progressively as I complete each week.

---

## 🛠️ How to Run

### C Programs (Weeks 1–5)

CS50 problems in C are designed to run in the [CS50 Codespace](https://cs50.dev/) environment, which comes pre-configured with the `cs50.h` library and `make`. You can also compile locally:

```bash
cd weekX/problem-name
make solution        # or: clang -o solution solution.c -lcs50
./solution
```

### Python Programs (Week 6+)

```bash
cd week6/problem-name
python solution.py
```

### Web Projects (Week 8–9)

```bash
cd week8/problem-name
# Open index.html in a browser, or for Flask:
cd week9/problem-name
flask run
```

> Some problems depend on the `cs50` library for C or Python. See [cs50.readthedocs.io](https://cs50.readthedocs.io/) for setup instructions outside the official codespace.

---

## 🗂️ Repository Structure

```
CS50X/
├── week1/
│   ├── hello/
│   ├── mario/
│   └── cash/
├── week2/
│   ├── scrabble/
│   └── caesar/
├── ...
└── final-project/
    └── README.md
```

---

## 🏁 Final Project

CS50X culminates in a **Final Project** — a fully self-designed program of your choice, in any language, on any topic. My final project will be documented in its own folder with a dedicated `README.md`, a short demo video, and full source code.

> *"The climax of CS50 and CS50X is its final project, in which you implement a project of your own in any language." — CS50 Staff*

---

## 🙋 About Me

I'm **Shivansh**, a first-year student pursuing B.Tech in Mechanical Engineering at IET Lucknow and BS in Data Science & Applications at IIT Madras simultaneously. I'm working through CS50X to build strong fundamentals in Computer Science — from pointers and memory to web apps — alongside my core engineering and data science curriculum.

---

## 📜 License

This repository is for **educational purposes only**. All problem statements, assets, and course content belong to Harvard University / CS50. My solutions are shared in good faith for the benefit of fellow learners and are not intended for academic dishonesty of any kind.

---

*"This is CS50." — David J. Malan*
