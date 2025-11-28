# Black Box Testing Techniques

Black Box Testing focuses on testing functionality without knowing internal code structure.

---

## 1. Equivalence Partitioning (EP)
Divide input data into valid and invalid partitions.

### Example:
Input age must be between 18 and 60
- Valid: 18–60
- Invalid: <18 and >60

---

## 2. Boundary Value Analysis (BVA)
Test the edges of the inputs.

### Example:
Range: 18–60
- Test: 17, 18, 60, 61

---

## 3. Decision Table
Used when output depends on multiple conditions.

| Condition A | Condition B | Output |
|-------------|-------------|--------|
| T           | T           | Approve |
| T           | F           | Reject |
| F           | T           | Reject |
| F           | F           | Reject |
