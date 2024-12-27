# Text Editor (C++)

## Overview
This project implements a functional text editor using **Linked List** and **Stack** data structures. Each line of text is stored as a node in a linked list, enabling efficient operations like insertion, deletion, and rearrangement. The **Stack** data structure powers the Undo feature, allowing users to revert their last actions.

The text editor provides basic editing capabilities and file handling, making it a compact yet powerful tool for text manipulation and a great example of data structure application in C++.

---

## Features

### File Operations:
- **Open an existing file:** Reads each line into a linked list.
- **Save changes to a file:** Write the current state of text to a file.

### Text Editing:
- **Insert:** Add text at a specified line.
- **Delete:** Remove a specific line of text.
- **Move:** Rearrange lines by moving line `n` to position `m`.
- **Replace:** Replace text in a specified line.

### Navigation:
- **Next Page:** Scroll to the next set of lines.
- **Previous Page:** Scroll back to earlier lines.

### Undo Feature:
- Undo the most recent action using a **Stack** data structure.  
  *Note: This feature may exhibit minor bugs.*

---

## Data Structure Details

### Linked List:
- Each line of text is stored in a node with:
  - A `data` field for the text.
  - A `next` pointer to the subsequent line.

### Stack:
- Stores previous states of the text to enable the **Undo** feature.


   

