# polynomial-solver
Find roots of a function.
For irrational or reocurring decimal numbers one must use an inequality with |y|<z for some z very small and close to zero to get a range of values close to the root.
This will effect both the roots and will give you a list of solutions depending on the step used in the range.
In theory could be used to find roots of any function, though inefficient however runs into problem as many functions such as sine and cosine have irrational roots thus opted
to try the program on polynomials.

                                                                                   
                                                                                   
Also, when working with np.arange the use of float arithemetic may give slightly inaccurate increase between steps if decimal thus a large range was used with a integer step, which was then divided to give the wanted range and the decimal step, avoiding the slight inaccuracy issue.                                                                                    
