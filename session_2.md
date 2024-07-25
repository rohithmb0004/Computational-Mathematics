## Pseudocode for Solution of a system of equations
```python
$$ FUNCTION solution(A,B):
  Create Augmented matrix:k=[A/B]
Reduce in Row Echelon form
Rank=Number of rows of Reduced Row Echelon form
if Rank(k)!=Rank(A):
  print(System is consistent)
else if
  solve using back substitution
END FUNCTION $$
```
