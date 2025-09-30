### Data and control structures

Here I solve some everyday problems using data and control structures in Python.

After reading this file, go to the **`data_and_control_structures.ipynb`**.
 
### Structure

- `data_and_control_structures.ipynb` descriptions of exercises and implementation process, and program code that performs all exercises
- `l1e3_text.txt` contains the text to run 'Level 1 Exercise 3. Word count of a text'
- `l1e4_dictionary.json` contains the dictionary to run 'Level 1 Exercise 4. Reverse dictionary'
- `l2e1_dictionary.json` contains the dictionary to run 'Level 2 Exercise 1. Reverse dictionary with duplicates'
- `l3e1_output.png` image contains output for 'Level 3 Exercise 1. Word counter and straightener of a text'
- `l3e1_text.txt` contains the text to run 'Level 3 Exercise 1. Word counter and straightener of a text'

### Implementation

I organized the code according to PEP 8 and PEP 257 standards. When working in a team, I would prioritize team agreements; however, in this case, I followed personal preferences. For example, the Google style for docstrings, style of variable and function names, location of main() function at the end of code, etc.

When splitting the algorithms into functions, I followed the principle of 'Functions should do one thing' and considered the potential need to reuse the function in the future. The latter also influenced the naming of variables. For example, if a function works exclusively in the context of calculating the Body Mass Index, the variables include 'bmi' in their names. Conversely, if the function could be applied to validate any input in the future, the names are more general, such as 'user_object', indicating the transformation of any or multiple object types.