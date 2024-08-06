# A Student's Guide to Python for Physical Modeling: Jupyter Notebook Edition

Welcome to the repository for the Jupyter Notebook version of code examples from the book *A Student's Guide to Python for Physical Modeling: Second Edition* by Jesse M. Kinder and Philip Nelson. This repository aims to complement the book with interactive Python code examples that are ideal for learning and experimentation.

## Overview

This repository includes Jupyter Notebooks for various chapters and topics covered in the book. The notebooks provide practical code examples and exercises to help you understand the concepts of Python programming for physical modeling.

### Table of Contents

1. [Introduction to Python for Scientific Computing](#chapter-1-introduction-to-python-for-scientific-computing)
2. [Introduction to Python Programming](#chapter-2-introduction-to-python-programming)
3. [Working with Arrays and Functions](#chapter-3-working-with-arrays-and-functions)
4. [Data Input and Output](#chapter-4-data-input-and-output)
5. [Visualization](#chapter-5-visualization)
6. [Numerical Methods](#chapter-6-numerical-methods)
7. [Advanced Topics](#chapter-7-advanced-topics)
8. [Convolution](#chapter-8-convolution)
9. [Random Walks](#chapter-9-random-walks)
10. [Epilogue](#epilogue)
11. [Appendix F: Scoping and Namespaces](#appendix-f-scoping-and-namespaces)
12. [Your Turn (Additional Exercises)](#your-turn-additional-exercises)
13. [Additional Files](#additional-files)
14. [Getting Started](#getting-started)
15. [Exploring the Code](#exploring-the-code)
16. [Additional Notes](#additional-notes)
17. [Screenshots](#screenshots)
18. [Contact](#contact)
19. [Author](#author)
20. [Acknowledgments](#acknowledgments)

## Chapter 1: Introduction to Python for Scientific Computing

- **1.1. Why Python for Scientific Computing?**
  - Open-source and free
  - Large and active community
  - Extensive libraries (NumPy, SciPy, Matplotlib, etc.)
  - Readability and ease of use

- **1.2. Basic Python Syntax**
  - Variables and data types
  - Operators
  - Basic input and output
  - Indentation and code blocks

- **1.3. Control Flow**
  - Conditional statements (if, else, elif)
  - Loops (for, while)
  - Examples: `string_format.ipynb`, `string_percent.ipynb`, `for_loop.ipynb`, `while_loop.ipynb`

- **1.4. Functions**
  - Definition, parameters, and return values
  - Scope and namespaces (`scope.ipynb`, `name_collision.ipynb`)

- **1.5. Introduction to NumPy**
  - NumPy arrays vs. Python lists
  - Basic array operations
  - Vectorization (`vectorize.ipynb`)
  - Additional Topics: Basic plotting (`simple_plot.ipynb`), File I/O (`import_text.ipynb`, `save_load.ipynb`, `print_write.ipynb`)

## Chapter 2: Introduction to Python Programming

- `string_format.ipynb`
- `string_percent.ipynb`
- `for_loop.ipynb`
- `while_loop.ipynb`
- `vectorize.ipynb`

## Chapter 3: Working with Arrays and Functions

- `projectile.ipynb`
- `branching.ipynb`
- `nesting.ipynb`

## Chapter 4: Data Input and Output

- `import_text.ipynb`
- `save_load.ipynb`
- `print_write.ipynb`

## Chapter 5: Visualization

- `simple_plot.ipynb`
- `graph_modifications.ipynb`
- `line3d.ipynb`
- `subplot.ipynb`
- `subplots.ipynb`

## Chapter 6: Numerical Methods

- `measurements.ipynb`
- `rotate.ipynb`
- `average.ipynb`
- `histogram.ipynb`
- `contour.ipynb`
- `matrix_inversion.ipynb`
- `quadrature.ipynb`
- `simple_oscillator.ipynb` (used in `solve_ode.ipynb`)
- `solve_ode.ipynb`
- `parametric_oscillator.ipynb`
- `ivp_comparison.ipynb`
- `vortex.ipynb`
- `gradient.ipynb`
- `streamlines.ipynb`

## Chapter 7: Advanced Topics

- `data_images.ipynb`
- `walker.ipynb`
- `waves.ipynb` (uses `html_movie.py`)

## Chapter 8: Convolution

- `convolution.ipynb`

## Chapter 9: Random Walks

- `first_passage.ipynb`
- `data_dictionary.ipynb` (requires `first_passage.ipynb`)
- `nd_random_walks.ipynb`

## Epilogue

- `surprise.ipynb`

## Appendix F: Scoping and Namespaces

- `scope.ipynb`
- `name_collision.ipynb`

## Your Turn (Additional Exercises)

- `fancy_plot.ipynb`
- `legend.ipynb`
- `measurements.ipynb` (different from Chapter 6 version)
- `random_walk.ipynb`
- `surface.ipynb`
- `regression.ipynb` (requires `first_passage.ipynb`)

## Additional Files

- `bar3d.ipynb`
- `html_movie.py` (used by `waves.ipynb`)
- `perrin.ipynb` (requires `g26perrindata.npy`)
- `shading.ipynb`
- `sympy_examples.py` (better suited for interactive use)

## Getting Started

1. **Clone this repository:**  
   ```bash
   git clone https://github.com/worachat-dev/Student-Guide-2Python4Physical-Modeling.git
   ```

2. **Install required libraries:**  
   The code examples rely on libraries such as NumPy, SciPy, and Matplotlib. Install them using pip:  
   ```bash
   pip install numpy scipy matplotlib
   ```

3. **Open a Jupyter Notebook:**  
   Navigate to the project directory and launch a Jupyter Notebook server:  
   ```bash
   cd a-students-guide-to-python-for-physical-modeling
   jupyter notebook
   ```
   This will open a web interface where you can browse and execute the Jupyter notebooks.

## Exploring the Code

Each notebook corresponds to a code fragment from the book, with explanations and comments embedded. Feel free to explore, modify, and experiment with the code to enhance your learning experience.

## Additional Notes

- Some examples may require additional data files not included in this repository. Refer to the book for instructions on obtaining these files.
- For a comprehensive understanding, we recommend reading the book alongside exploring these notebooks.

We hope this repository enhances your learning of Python for physical modeling.

## Screenshots

![The Python Standard Library](./image.png)

## Contact

For any inquiries or issues, please contact me!

## Author

- **Worachat W, Dev.** - *Data Science, Engineering & Full Stack Dev. 2024*  
  [LinkedIn](https://www.linkedin.com/in/brainwaves-your-ai-playground-82155961/) | [GitHub](https://github.com/worachat-dev) | [Facebook](https://web.facebook.com/NutriCious.Thailand)

## Acknowledgments

- The code and explanations are derived from *A Student's Guide to Python for Physical Modeling: Second Edition* by Jesse M. Kinder and Philip Nelson. We are grateful for their contribution to scientific computing education.
- This project uses Jupyter Notebook, an interactive computational environment for Python ([Jupyter](https://jupyter.org/)). We acknowledge the Jupyter Project for creating this valuable tool.
