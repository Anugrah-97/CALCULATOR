# 🧮 Simple Python Calculator

This is a simple Python function that acts as a calculator.  
It performs operations based on the operator provided.

---

## 📌 Function Definition

```python
def calculator(a, b, operator):
    if operator == "+":
        print(a + b)
    elif operator == "-":
        print(a - b)
    elif operator == "%":
        print(a % b)
    else:
        print(a ** b)

# Example usage
calculator(6, 7.2, '**')
