# Theory of Computer Science – JFLAP Assignment

## DFA – Deterministic Finite Automata

### Question 1 – DFA for Strings Ending with `00`

**Design a DFA for the language accepting strings ending with `00` over input alphabets `{0, 1}`.**

**Language:**

`L = {00, 100, 1100, 111100, …}`

---

### Question 2 – DFA for Strings Beginning with `0`

**Design a DFA that accepts all strings beginning with `0` over Σ = `{0, 1}`.**

**Language:**

`L = {0, 01, 0001, 010, 01111, …}`

---

### Question 3 – DFA for Strings Having Substring `bab`

**Design a DFA that accepts all strings having substrings `bab` over Σ = `{a, b}`.**

**Language:**

`L = {bab, ababb, bbab, abab, baba, babba}`

---

### Question 4 – DFA for Strings with `0` and `1` Only

**Design a DFA for the language accepting strings with `0` and `1` only over input alphabets `{0, 1}`.**

**Language:**

`L = {0, 1, 00, 11, 000, 1111, …}`

---

### Question 5 – DFA for Strings Containing `01` or `10`

**Design a DFA for the language accepting strings containing `01` or `10` as a substring over input alphabets Σ = `{0, 1}`.**

**Language:**

`L = {10, 01, 100, 010, …}`

---

## NFA – Non-Deterministic Finite Automata

### Question 6 – NFA for Strings Starting and Ending with the Same Symbol

**Design a NFA that accepts all strings over alphabet Σ = `{a, b}` such that every accepted string start and end with same symbol.**

---

### Question 7 – NFA for Strings Containing `101`

**Design an NFA to recognize the language consisting of all strings containing one or more instances of `101` over alphabet Σ = `{0, 1}`.**

---

## NFA to DFA Conversion

### Question 8 – Convert NFA to DFA

**Convert given NFA to DFA.**

The solution contains the NFA transition table and the corresponding DFA state transition diagram and transition table.

---

### Question 9 – Convert NFA to DFA

**Convert given NFA to DFA.**

The solution contains the NFA transition table, DFA transition table, and DFA state transition diagram.

---

### Question 10 – Convert NFA to DFA

**Convert given NFA to DFA.**

The solution contains the NFA transition table, DFA transition table, and DFA state transition diagram. A dead state `∅` is used wherever required.

---

## Directory Structure

```text
TOC-JFLAP-Assignments/
│
├── DFA/
│   ├── DFA_Q1_ends_with_00.jff
│   ├── DFA_Q2_starts_with_0.jff
│   ├── DFA_Q3_substring_bab.jff
│   ├── DFA_Q4_strings_with_0and1only.jff
│   └── DFA_Q5_strings_with_01or10.jff
│
├── NFA/
│   ├── NFA_Q6_strings_same_start_and_end.jff
│   └── NFA_Q7_substrings_with_101.jff
│
├── NFA-to-DFA/
│   ├── NFAtDFA_Q8.jff
│   ├── NFAtDFA_Q9.jff
│   └── NFAtDFA_Q10.jff
│
└── README.md
```

**Author:** **Bhagyashri Joshi**

**Class: D12B**

**Roll no.: 23**
