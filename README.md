# 📄 Less & More — CLI File Viewing Challenge

This repository contains a three-part Linux terminal exercise designed to explore advanced viewing techniques using `less` and `more`. You'll learn how to display files with line numbers, compress blank lines, and combine both features—all through man-page mastery.

## 🧩 Scenario

You're given a file named `sample.txt` and asked to perform three distinct viewing operations using only `less` and `more`. Each task builds on your understanding of CLI file navigation and formatting.

## 🧪 Tasks

### 1️⃣ View `sample.txt` with Line Numbers (Using `less`)
Expected output:
```
  1 This sample is based hugely on the original sample.txt produced
  2
  3
  4
  5 I used the following options to convert this document:
```

### 2️⃣ View `sample.txt` with Consecutive Blank Lines Compressed (Using `more`)
Expected output:
```
This sample is based hugely on the original sample.txt produced

I used the following options to convert this document:
```

### 3️⃣ View `sample.txt` with Line Numbers and Compressed Blank Lines (Using `less`)
Expected output:
```
  1 This sample is based hugely on the original sample.txt produced
  2
  5 I used the following options to convert this document:
```

## 🚫 Constraints

- Only `less` and `more` commands are allowed.
- Each command must be written on a separate line.
- No use of `cd`, `cat`, or other utilities.
- You may use pipelines and redirection if needed.

## 🚀 Submission

Submit your solution either directly or via a script file named `solution.sh`.

---

Master the terminal. Impress your team. 🧠💻
