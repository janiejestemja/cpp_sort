# PythonC-API
--- 

> Boilerplate for [CI action](https://github.com/janiejestemja/py_sort)

## Building the cpp module
---

To build the module:

Ensure `g++` is installed:
```bash
g++ --version
```

Verify necessary headers are in place with:
```bash
dnf list --installed | grep python3-devel
```

Run setup script:
```bash
python setup.py bdist_wheel
```
