# Python File Handling Assignment 

Welcome to my Python File Handling project! This repository contains practical exercises focused on learning how to work with files, process data, and handle inputs and outputs in Python.

---

## 🛠️ Tasks Completed

* **Task 1:** Write and read basic sales records using text files (`sales_data.txt`).
* **Task 2:** Explore different file reading methods like `.read()`, `.readline()`, and `.readlines()`.
* **Task 3:** Append new sales data dynamically to an existing file.
* **Task 4:** Generate a summary report calculating total, highest, lowest, and average sales.
* **Task 5:** Capture user input for product names and prices, storing them in `products.txt`.
* **Task 6:** Implement safe file reading using `os.path.exists()` for error handling.
* **Task 7:** Mini project calculating discounted prices and exporting a complete summary report (`discount_report.txt`).

---

##  Key Python Concepts & Methods Used

* **File Modes:**
  * `"w"`: Write mode (creates a new file or overwrites an existing one).
  * `"r"`: Read mode (reads content from an existing file).
  * `"a"`: Append mode (adds new content to the end of a file without erasing old data).
  * `"w+"`: Write and read mode combined.

* **File Operations & Context Managers:**
  * `open()` / `close()`: Opens and closes connection to files.
  * `with open(...) as file:`: A safe context manager that automatically closes the file when the block of code finishes.

* **Reading Methods:**
  * `.read()`: Reads the entire file content as a single string.
  * `.readline()`: Reads just the first line of the file.
  * `.readlines()`: Reads all lines into a list where each element represents a line.

* **String & Data Formatting:**
  * `.strip()`: Removes unnecessary newline characters (`\n`) and trailing/leading white spaces.
  * `",".join()`: Joins items of a list into a single string separated by commas.
  * `map()`: Applies a conversion function across list elements (e.g., mapping elements to integers or strings).

* **System Safeguards:**
  * `os.path.exists()`: Checks if a file path exists before attempting to open it, preventing file-not-found errors.

---

##  How to Run

1. Make sure you have Python installed on your computer.
2. Clone or download this repository.
3. Open your terminal or VS Code inside the folder and run any of the Python files or the Jupyter Notebook (`.ipynb`).
