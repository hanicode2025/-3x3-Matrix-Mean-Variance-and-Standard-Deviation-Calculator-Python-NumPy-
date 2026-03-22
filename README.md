# Mean, Variance, and Standard Deviation Calculator

**Overview:**  
Python project that builds a calculator using NumPy to compute key statistics—mean, variance, standard deviation, max, min, and sum—on a 3×3 matrix. Results are returned along columns, rows, and for the flattened matrix. Includes input validation to ensure exactly 9 numbers are provided.

**Technologies Used:**  
- Python 3.x  
- NumPy  

**Features:**  
- Compute mean, variance, standard deviation, max, min, and sum  
- Returns statistics along:  
  - Axis 0 (columns)  
  - Axis 1 (rows)  
  - Flattened matrix  
- Input validation for 9-number lists  

**Usage Example:**  
```python
from mean_var_std import calculate

input_list = [1, 2, 3, 4, 5, 6, 7, 8, 9]
results = calculate(input_list)
print(results)
{
 'mean': [[4.0, 5.0, 6.0], [2.0, 5.0, 8.0], 5.0],
 'variance': [[6.0, 6.0, 6.0], [0.6667, 0.6667, 0.6667], 6.6667],
 'standard deviation': [[2.4495, 2.4495, 2.4495], [0.8165, 0.8165, 0.8165], 2.5820],
 'max': [[7, 8, 9], [3, 6, 9], 9],
 'min': [[1, 2, 3], [1, 4, 7], 1],
 'sum': [[12, 15, 18], [6, 15, 24], 45]
}

mean-var-std-calc/
├── mean_var_std.py     # Main Python script for calculations
└── README.md           # Project documentation



---

If you want, I can also **draft a consistent style README for all your ML/Data repos**, so your GitHub looks **professional, recruiter-ready, and LinkedIn-aligned**.  

Do you want me to do that next?
