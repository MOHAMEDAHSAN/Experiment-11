### Name : S Mohamed Ahsan
### Reg No : 212223240089

# **Experiment – 11** : Pytest Installation


### **Aim:**

To install and configure **Pytest**, a Python testing framework, and verify its successful installation.

---

### **Theory (Pytest):**

* **Pytest** is a popular testing framework in Python used to write simple as well as scalable test cases.
* It is more flexible and user-friendly compared to Python’s built-in `unittest` module.
* Features:

  1. Simple syntax for writing test functions.
  2. Automatic discovery of test files and functions.
  3. Detailed reports with minimum code.
  4. Supports fixtures, parameterization, and plugins.

---

### **Procedure:**

1. Open the terminal/command prompt.
2. Check Python and pip installation:

   ```bash
   python --version
   pip --version
   ```
3. Install Pytest using pip:

   ```bash
   pip install pytest
   ```
4. Verify installation by checking the version:

   ```bash
   pytest --version
   ```
5. Create a sample test file `TEST_EX11.py` with the following code:

   ```python
   def func(x):
       return x + 1

   def test_answer():
       assert func(3) == 4
   ```
6. Run the test using the command:

   ```bash
   pytest
   ```

---

### **Output:**
<img width="1187" height="304" alt="image" src="https://github.com/user-attachments/assets/48921117-a927-4793-9fe4-950b62d4f825" />
<img width="1038" height="180" alt="image" src="https://github.com/user-attachments/assets/638b9d6d-b910-4539-a103-8f73532ef41f" />


---

### **Result:**

Pytest was successfully installed and verified by running a sample test case.

