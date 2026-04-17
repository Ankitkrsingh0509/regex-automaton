# 🚀 Regex to Automaton Visualizer

An interactive web-based tool to convert **Regular Expressions (Regex)** into different types of **Finite Automata** with step-by-step visualization.

---

## 🧠 Overview

This project converts a given regex into:

* ε-NFA (Thompson Construction)
* NFA (ε-removal)
* DFA (Subset Construction)
* Minimized DFA (Equivalence & Myhill-Nerode)

It is designed for both **visualization** and **learning**, making automata concepts easier to understand.

---

## ✨ Features

* 🔹 Regex input with validation
* 🔹 Full conversion pipeline (Regex → ε-NFA → NFA → DFA → Minimized DFA)
* 🔹 Step-by-step algorithm explanation
* 🔹 Interactive graph visualization
* 🔹 String simulation (Accept/Reject)
* 🔹 Transition table & statistics
* 🔹 Manual automaton builder (draw your own)
* 🔹 Built-in learning section (theory + diagrams)

---

## 🖥️ How to Use

1. Open the `regex-automaton.html` file in your browser
2. Enter a regex (e.g. `(a|b)*abb`)
3. Click **Build**
4. Switch between:

   * ε-NFA
   * NFA
   * DFA
   * Minimized DFA
5. Use tabs to:

   * View steps
   * Simulate strings
   * Analyze automaton
   * Learn concepts

---

## 🧪 Example

```
(a|b)*abb
```

---

## ⚙️ Tech Stack

* HTML5
* CSS3
* JavaScript (Vanilla)
* SVG (for visualization)

---

## 📦 Requirements

No dependencies required.

```
# requirements.txt
# (empty)
```

---

## 🎯 Purpose

This project helps in:

* Understanding Automata Theory
* Visualizing regex conversions
* Learning core algorithms interactively

---

## 📌 Note

Best suited for students studying:

* Theory of Computation
* Compiler Design
* Formal Languages

---

