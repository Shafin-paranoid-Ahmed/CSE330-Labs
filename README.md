# CSE330 Labs — Numerical Methods

A notebook collection for turning numerical-method formulas into Python calculations and plots. The labs focus on polynomial interpolation and numerical differentiation, with practice and coding-exam notebooks alongside them.

## Contents

| Location | Topic |
| --- | --- |
| [Lab 01](Lab/Lab%2001/) | Python fundamentals |
| [Lab 02](Lab/Lab%2002/) | Polynomial representation and interpolation |
| [Lab 03](Lab/Lab%2003/) | Lagrange interpolation |
| [Lab 04](Lab/Lab%2004/) | Newton's divided-difference interpolation |
| [Lab 05](Lab/Lab%2005/) | Numerical differentiation and Richardson extrapolation |
| [Practice notebook](Lab/practice.ipynb) | Additional interpolation and differentiation exercises |
| [Coding exam](Lab/Copy%20of%20CSE330_CodingExam_Sec05.ipynb) | Assessment exercises |

Some lab folders also include the assignment PDF.

## Open the notebooks

Use Python 3 with Jupyter or Google Colab. The notebooks import NumPy and Matplotlib; the practice notebook also imports pandas.

For local use:

```bash
python -m pip install jupyterlab numpy matplotlib pandas
python -m jupyterlab
```

Open a notebook under `Lab/` and execute its cells in order. Start with Lab 01 if you want the Python introduction, or Lab 02 for the numerical-method sequence.

The code includes custom polynomial classes, worked calculations, and plots. Read the exercise text together with the implementation and vary the supplied points or step sizes to explore the result.

## Scope

This repository preserves coursework, including instructional scaffolding, implementation attempts, and saved notebook outputs. Dependency versions are not pinned, and the notebooks have not been rerun as part of this documentation update. Saved plots and outputs describe earlier notebook sessions.
