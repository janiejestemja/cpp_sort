# PythonC-API

--- 

> Boilerplate

## Building the cpp module

---

To build the module:

1. Ensure `g++` is installed:
   ```bash
   g++ --version
   ```
2. Verify necessary headers are in place with:
   ```bash
   dnf list --installed | grep python3-devel
   ```
3. Run setup script:
   ```bash
   python setup.py bdist_wheel
   ```
