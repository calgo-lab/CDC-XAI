## Overview

This framework combines three main components: **error detection**, **error correction**, and **error explanation**.  
It detects and corrects data errors, and explains why the model flagged a value as incorrect, including which features contributed to that decision.

The framework uses datasets from the PMLB repository:  
https://github.com/EpistasisLab/pmlb

---

## How to Run the Project

There are two ways to run the framework:

### Option 1: Run CDC.ipynb

- This notebook contains the full implementation.
- Scroll down to the user input interface section.
- Modify the parameters and run the project.
- Use this option if you want to see or edit the full code.

### Option 2: Run setup.ipynb

- This notebook calls CDC.ipynb and runs it automatically.
- It shows only the user interface, which makes it easier to use.
- If you want to call the code externally using this method, comment out the user interface section inside CDC.ipynb.
