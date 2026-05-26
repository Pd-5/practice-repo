# Naive Pattern Matching Algorithm

This project implements the **Naive String Matching Algorithm** using Python.

The program searches for a pattern inside a text and returns the starting index of the first occurrence of the pattern.

## Algorithm Used

### Naive String Matching Algorithm

The algorithm checks the pattern at every possible position in the text.

Example:

Text : banana  
Pattern : ana

Checks:

ban  
ana ← Match Found  
nan  
ana  

Output:

1

---

## Time Complexity

| Case | Complexity |
|------|-------------|
| Best Case | O(n) |
| Average Case | O(mn) |
| Worst Case | O(mn) |

Where:

- `m` = Length of text
- `n` = Length of pattern

---

## Author
Priyadharshini V
