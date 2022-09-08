# CVXPY
- CVXOPT is a free software package for convex optimization based on the Python programming language. 
- It can be used with the interactive Python interpreter, on the command line by executing Python scripts, or integrated in other software via Python extension modules. 
- Its main purpose is to make the development of software for convex optimization applications straightforward by building on Python’s extensive standard library and on the strengths of Python as a high-level programming language
***

## CVXPY vs. CVXOPT
- According to cvxpy they use cvxopt libraries to solve the problems. In cvxopt you have to write your problem in a more standard way for the type of solver you want to use, whereas cvxpy is supposed to adapt your problem based on the structure you use for your problem (they are supposed to select the type of cvxopt solver depending on your problem and pass the variables in an standard cvxopt way). **At the end of the day CVXPY is a wrapper that tries to make things easier.**


## References
- [CVXOPT](https://cvxopt.org/userguide/coneprog.html) 
- [Why I migrated PyPortfolioOpt from scipy to cvxpy](https://www.reddit.com/r/algotrading/comments/ftmfem/why_i_migrated_pyportfolioopt_from_scipy_to_cvxpy/)
- [What is the fastest way to minimize a function in python?](https://stackoverflow.com/questions/43648073/what-is-the-fastest-way-to-minimize-a-function-in-python)
- [scipy.optimize vs. CVXPY](https://kevintcarlberg.net/files/opt_class_icme/4_optimization-in-python.pdf)
- [Differences btw CVXOPT and CVXPY](https://stackoverflow.com/questions/30647436/from-cvx-to-cvxpy-or-cvxopt)
- [Tutorials](https://www.cvxpy.org/examples/index.html#)