# Ex7_1 - String Reversal App

A Java console application that reverses a user-entered string using both an **iterative** and **recursive** approach.

---

## 📋 Description

This program demonstrates two different algorithmic approaches to reversing a string in Java:

- **Iterative** – uses a `for` loop to build the reversed string character by character
- **Recursive** – uses a recursive method that peels off the last character and calls itself on the remaining substring

---

## 🗂️ Project Structure

```
Ex7_1_StringReversal/
├── src/
│   └── StringReversalApp.java
├── bin/
├── .project
└── .classpath
```

---

## 🚀 How to Run

### In Eclipse
1. Import the project: `File → Import → Existing Projects into Workspace`
2. Select the `Ex7_1_StringReversal` folder
3. Right-click `StringReversalApp.java` → `Run As → Java Application`
4. Enter a string when prompted in the console

### In Terminal
```bash
cd Ex7_1_StringReversal
javac -d bin src/StringReversalApp.java
java -cp bin StringReversalApp
```

---

## 💻 Sample Output

```
Enter string to reverse:
hello
Iterative string reversal...
olleh
Recursive string reversal...
olleh
```

---

## 🧠 Methods

| Method | Type | Description |
|---|---|---|
| `iterReverse(String str)` | Iterative | Loops from last index to 0, builds reversed string |
| `recReverse(String str)` | Recursive | Base case: length ≤ 1. Recursive case: last char + recReverse of the rest |

---

## 📚 Course Info

- **Course:** Java Programming
- **Chapter:** 17 – Recursion
- **Exercise:** 7-1
