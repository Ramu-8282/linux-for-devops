# pwd Command

## 📖 What is `pwd`?

The `pwd` (Print Working Directory) command displays the absolute path of the directory you are currently working in.

It is one of the most frequently used Linux commands because it helps you identify your current location in the filesystem.

---

## 🎯 Why is it Important?

When working on Linux servers, it's easy to lose track of your location after navigating through multiple directories.

Using `pwd` helps you verify your current working directory before creating, modifying, or deleting files.

---

## 📝 Syntax

```bash
pwd
```

---

## 💻 Example

```bash
pwd
```

Output

```text
/home/ramu/Projects/Linux---For-Devops
```

---

## 📌 Explanation

- `pwd` takes no arguments.
- It prints the absolute path of your current directory.
- It helps prevent mistakes when working with files and folders.

---

## 🌍 Real-World DevOps Scenario

Imagine you're connected to a production Linux server using SSH.

Before deploying an application or editing configuration files, you should always verify your current directory.

Example:

```bash
pwd
```

Output

```text
/var/www/html
```

Now you know you're inside the web server's document root before making any changes.

---

## 🧪 Practice Lab

### Task 1

Navigate to your project directory.

```bash
cd ~/Projects/Linux---For-Devops
```

Run

```bash
pwd
```

Expected Output

```text
/home/ramu/Projects/Linux---For-Devops
```

---

### Task 2

Move to the root directory.

```bash
cd /
```

Run

```bash
pwd
```

Expected Output

```text
/
```

---

### Task 3

Move back to your home directory.

```bash
cd ~
```

Run

```bash
pwd
```

Expected Output

```text
/home/ramu
```

---

## ⚠️ Common Mistakes

❌ Assuming you know your current directory.

Always verify it using:

```bash
pwd
```

This helps prevent accidental file modifications or deletions.

---

## 🎤 Interview Question

### Q1. What does `pwd` stand for?

**Answer:**

Print Working Directory.

It displays the absolute path of the current directory.

---

## 📝 Summary

- Displays the current directory.
- Shows the absolute path.
- Does not require any arguments.
- Commonly used before performing file operations.
- Frequently used by Linux administrators and DevOps Engineers.

