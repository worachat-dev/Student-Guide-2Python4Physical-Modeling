## A Student's Guide to Python for Physical Modeling: Jupyter Notebook Edition

This repository provides Jupyter Notebook versions of the code examples found in the book *A Student's Guide to Python for Physical Modeling: Second Edition* by Jesse M. Kinder and Philip Nelson ([https://www.amazon.com/Students-Guide-Python-Physical-Modeling/dp/0691180563](https://www.amazon.com/Students-Guide-Python-Physical-Modeling/dp/0691180563)).

**Chapter 1: Introduction to Python for Scientific Computing**

**1.1. Why Python for Scientific Computing?**
**Briefly discuss the advantages of Python in scientific computing:**
Open-source and free
Large and active community
Extensive libraries (NumPy, SciPy, Matplotlib, etc.)
Readability and ease of use

**1.2. Basic Python Syntax**
**Introduce fundamental Python concepts:**
Variables and data types (integers, floats, strings, booleans)
Operators (arithmetic, comparison, logical)
Basic input and output (print, input)
Indentation and code blocks

**1.3. Control Flow**
Explain conditional statements (if, else, elif)
Discuss loops (for, while)
Provide examples using code fragments: string_format.ipynb, string_percent.ipynb, for_loop.ipynb, while_loop.ipynb

**1.4. Functions**
Define functions and their importance
Explain function parameters, return values
Introduce scope and namespaces (referencing scope.ipynb and name_collision.ipynb)

**1.5. Introduction to NumPy**
Explain NumPy arrays and their advantages over Python lists
Demonstrate basic array operations (creation, indexing, slicing)
Introduce vectorization (using vectorize.ipynb)
Potential Additional Topics (Depending on Book's Scope)
Basic plotting using Matplotlib (referencing simple_plot.ipynb)
File I/O (referencing import_text.ipynb, save_load.ipynb, print_write.ipynb)

**Chapter 2: Introduction to Python Programming**

string_format.ipynb
string_percent.ipynb
for_loop.ipynb
while_loop.ipynb
vectorize.ipynb

**Chapter 3: Working with Arrays and Functions**

projectile.ipynb
branching.ipynb
nesting.ipynb

**Chapter 4: Data Input and Output**

import_text.ipynb
save_load.ipynb
print_write.ipynb

**Chapter 5: Visualization**

simple_plot.ipynb
graph_modifications.ipynb
line3d.ipynb
subplot.ipynb
subplots.ipynb


**Chapter 6: Numerical Methods**

measurements.ipynb
rotate.ipynb
average.ipynb
histogram.ipynb
contour.ipynb
matrix_inversion.ipynb
quadrature.ipynb
simple_oscillator.ipynb (used in solve_ode.ipynb)
solve_ode.ipynb
parametric_oscillator.ipynb
ivp_comparison.ipynb
vortex.ipynb
gradient.ipynb
streamlines.ipynb

**Chapter 8: Advanced Topics**

data_images.ipynb
walker.ipynb
waves.ipynb (uses html_movie.py)

**Chapter 9: Convolution**

convolution.ipynb

**Chapter 10: Random Walks**

first_passage.ipynb
data_dictionary.ipynb (requires first_passage.ipynb)
nd_random_walks.ipynb

**Epilogue**

surprise.ipynb

**Appendix F: Scoping and Namespaces**

scope.ipynb
name_collision.ipynb

**Your Turn (Additional Exercises)**

fancy_plot.ipynb
legend.ipynb
measurements.ipynb (different from Chapter 6 version)
random_walk.ipynb
surface.ipynb
regression.ipynb (requires first_passage.ipynb)

**Additional Files** 

bar3d.ipynb
html_movie.py (used by waves.ipynb)
perrin.ipynb (requires g26perrindata.npy)
shading.ipynb
sympy_examples.py (better suited for interactive use)


**Getting Started**

1. **Clone this repository:**  
   Bash  
   `git clone https://github.com/your-username/a-students-guide-to-python-for-physical-modeling.git`

   Replace your-username with your actual GitHub username.  
2. **Install required libraries:**  
   The code examples in this repository rely on several Python libraries, including NumPy, SciPy, and Matplotlib. You can install them using pip:  
   Bash  
   `pip install numpy scipy matplotlib`

3. **Open a Jupyter Notebook:**  
   Navigate to the project directory using your terminal and launch a Jupyter Notebook server:  
   Bash  
   `cd a-students-guide-to-python-for-physical-modeling`  
   `jupyter notebook`

   This will open a web interface where you can browse and execute the Jupyter notebooks.

**Exploring the Code**

Each Jupyter notebook corresponds to a code fragment from the book, with explanations and comments embedded within the code. Feel free to explore the notebooks, modify the code, and experiment\!


**Additional Notes**

* Some code examples may require additional data files that are not included in this repository. Please refer to the book for instructions on obtaining these data files.  
* The book provides a more comprehensive explanation of the concepts covered in the code examples. We highly recommend reading the book alongside this repository for a deeper understanding of the material.

We hope this repository provides a valuable resource for learning Python for physical modeling using Jupyter notebooks.

## Screenshots

![The Python Standard Library](./image.png)

## Contact

For any inquiries or issues, please contact me.!

## Author

- **Worachat W, Dev.** - *Data Science, Engineering & Full Stack Dev. 2024* 
[LinkedIn](https://www.linkedin.com/in/brainwaves-your-ai-playground-82155961/) | [GitHub](https://github.com/worachat-dev) | [Facebook](https://web.facebook.com/NutriCious.Thailand)

**Acknowledgments**

* The original code and explanations in this project are derived from the book *A Student's Guide to Python for Physical Modeling: Second Edition* by Jesse M. Kinder and Philip Nelson. We are grateful for their contribution to scientific computing education.  
* This project utilizes Jupyter Notebook, an interactive computational environment for Python ([https://jupyter.org/](https://jupyter.org/)). We acknowledge the Jupyter Project for creating this valuable tool.
